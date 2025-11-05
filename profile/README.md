# ⚔️ Folkhart

An idle RPG game with crafting, dungeons, and character progression. Build your character, enhance equipment, explore dungeons, and join guilds!

## 🎮 Features

- **5 Character Classes**: Warrior, Mage, Ranger, Cleric, Rogue with unique equipment
- **Equipment System**: 9 slots with visual enhancement levels (+1 to +9)
- **Blacksmith System**: Enhance, refine, and socket equipment
- **Socket & Gem System**: Up to 3 sockets per item with stat-boosting gems
- **Dungeon Exploration**: Idle and active modes with class-specific loot
- **Personal Shop**: Daily gem rewards and item purchasing
- **Achievement System**: Unlock titles and permanent stat bonuses
- **Guild System**: Join guilds and progress together

## 🛠️ Tech Stack

### Frontend
- React 18 + TypeScript
- PixiJS 7 (pixel art rendering)
- Tailwind CSS
- Zustand (state management)
- React Query (server state)
- Socket.io-client (real-time updates)

### Backend
- Node.js + Express (TypeScript)
- PostgreSQL + Prisma ORM
- Redis (caching & idle progression)
- Bull (background jobs)
- Socket.io (WebSocket)
- JWT Authentication

## 📱 Game Structure

### 5 Main Tabs
- **⚔️ Adventure** - Active/Idle combat, dungeon runs
- **🏠 Village** - Rest, upgrade equipment, manage companions
- **👥 Guild** - Co-op dungeons, guild chat, shared progression
- **🎒 Inventory** - Equipment, consumables, loot management
- **⚙️ Settings** - Profile, stats, monetization, logout

## 🎯 Roadmap

### Phase 1: Core Systems ✅
- [x] Character creation & 5 classes
- [x] Equipment system (9 slots)
- [x] Inventory management
- [x] Dungeon system (idle & active)
- [x] Blacksmith (enhancement, refining, socketing)
- [x] Shop system with daily gems
- [x] Achievement system
- [x] Mobile-responsive UI

### Phase 2: Social Features (In Progress)
- [x] Guild system (basic)
- [x] Guild chat
- [x] Friend system

### Phase 3: Content Expansion
- [x] More zones & dungeons
- [x] Companion system (database ready)
- [x] Crafting recipes
- [ ] Daily quests & events
- [ ] PvP arena

### Phase 4: Polish & Monetization
- [ ] Premium currency shop
- [ ] Battle pass
- [ ] Cosmetic items
- [ ] Performance optimization

## 📄 License

MIT License - See LICENSE file for details

## 📖 Documentation

- **[QUICKSTART.md](QUICKSTART.md)** - Get started in 5 minutes
- **[SETUP.md](SETUP.md)** - Detailed setup instructions
- **[DEVELOPMENT.md](DEVELOPMENT.md)** - Architecture and development guide
- **[PROJECT_SUMMARY.md](PROJECT_SUMMARY.md)** - Complete project overview

## 🎮 Game Features

### Character Classes
- **⚔️ Warrior** - Tanky melee fighter with high defense
- **🔮 Mage** - High damage spellcaster with low defense
- **🏹 Ranger** - Quick ranged attacker with balanced stats
- **✨ Cleric** - Support class with healing abilities
- **🗡️ Rogue** - Fast assassin with critical strikes

### Game Modes
- **Idle Farming** - Earn resources while AFK (up to 8 hours)
- **Dungeon Runs** - Active or Idle mode (1.5x rewards for active)
- **Equipment System** - Weapons, armor, and accessories
- **Companion System** - Pets that boost your stats (database ready)

### Progression
- Level up your character
- Unlock new zones and dungeons
- Collect rare loot
- Upgrade equipment
- Join guilds (Phase 2)

## 🎨 Tech Highlights

- **Mobile-First Design** - Optimized for phones and tablets
- **Real-time Updates** - WebSocket notifications for events
- **Background Jobs** - Idle progression calculated server-side
- **Type-Safe** - Full TypeScript on frontend and backend
- **Scalable** - Redis caching, Bull queues, Prisma ORM

## 🤝 Contributing

This is a personal project, but suggestions and feedback are welcome!
