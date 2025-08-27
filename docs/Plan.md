# Streamora Documentation 📖

This folder contains all documentation for the **Streamora** project.  

---

## 📌 Project Overview
Streamora is a modern social media app designed for creators and communities.  
It combines:
- **Content sharing** (posts, images, short videos)
- **Live interaction** (chat, notifications, reactions)
- **Digital economy tools** (payments, creator monetization)

---

## 🗂 Planned Documentation
1. **Project Plans**
   - Roadmap
   - Feature milestones
   - Release cycles

2. **Database Schema**
   - Users
   - Posts
   - Messages
   - Payments/Transactions

3. **API Guide**
   - Authentication
   - User management
   - Content posting
   - Messaging
   - Payments

4. **Roadmap**
   - MVP (Minimum Viable Product)
   - Beta release
   - Public launch

---

## 🛢 Example Database Schema (Draft)
- **Users**
  - `id`
  - `username`
  - `email`
  - `password_hash`
  - `profile_pic`
  - `created_at`

- **Posts**
  - `id`
  - `user_id` → references `Users`
  - `content` (text/media URL)
  - `created_at`

- **Messages**
  - `id`
  - `sender_id`
  - `receiver_id`
  - `message_text`
  - `sent_at`

- **Payments**
  - `id`
  - `user_id`
  - `amount`
  - `currency`
  - `method` (Flutterwave, PayPal, Crypto)
  - `status`
  - `created_at`

---

## 🚀 Roadmap (High Level)
- [ ] Set up backend (Node.js or Supabase)
- [ ] Create Flutter mobile app scaffold
- [ ] Design database schema
- [ ] Build authentication system
- [ ] Implement content posting
- [ ] Add real-time chat
- [ ] Enable payments
- [ ] Beta test release
