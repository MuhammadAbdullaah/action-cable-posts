# Action Cable Posts

A Ruby on Rails application showcasing real-time updates using **Action Cable** and **Turbo Streams**. The app allows users to create and manage posts dynamically, with real-time broadcasting to all connected users.

---

## Features

- **Real-Time Updates**: Posts are broadcast in real-time using Action Cable.
- **Turbo Streams**: Posts are dynamically appended to the page without requiring a reload.
- **CRUD Functionality**: Full Create, Read, Update, and Delete operations for posts.
- **User Authentication**: Posts are linked to the authenticated user.
- **Modern Rails Features**: Leverages Turbo, Hotwire, and WebSockets for a seamless user experience.

---

## Prerequisites

Before setting up the application, ensure you have the following installed:

- **Ruby**: Version `3.1.3`
- **Rails**: Version `7.x`
- **PostgreSQL**: As the database
- **Redis**: For WebSocket connections

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/MuhammadAbdullaah/action-cable-posts.git
cd action-cable-posts
