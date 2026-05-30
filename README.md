# Network Operations Toolkit

A modern, responsive web application for Network Engineers - an all-in-one daily operations toolkit with professional dashboard UI, dark/light mode support, and comprehensive network diagnostic tools.

## 🎯 Features

### Dashboard Home
- Overview cards for tools
- Quick access menu
- Recent activities/history
- Searchable command bar
- Network-themed UI design

### Network Diagnostic Tools
- **Ping Tool** - ICMP echo requests with statistics
- **Traceroute Tool** - Route tracing to destination
- **DNS Lookup** - DNS resolution and reverse lookup
- **Port Checker** - TCP/UDP port availability testing
- **IP Subnet Calculator** - CIDR calculations and subnet analysis
- **Bandwidth Calculator** - Data rate conversions
- **IP Address Validator** - IPv4/IPv6 validation
- **Latency Monitor** - Real-time latency tracking

### SSH Terminal Section
- Browser-based SSH client
- Multiple device profiles
- Tabbed terminal sessions
- Command history
- Auto-reconnect support

### iPerf Testing Tool
- Client/server mode selection
- TCP and UDP testing
- Bandwidth, duration, port configuration
- Throughput graphs and statistics
- Export results (PDF/CSV)

### Command Libraries

#### Cisco CLI Reference
- Routing, Switching, VLAN, OSPF, BGP
- STP, ACL, NAT, Interface troubleshooting
- Searchable database with examples
- Copy-to-clipboard functionality

#### FortiGate Firewall
- Troubleshooting commands
- VPN commands
- HA status commands
- Session debugging

#### A10 Load Balancer
- Configuration generator
- Virtual server setup
- Backend server management
- Health checks and load balancing
- SSL offloading
- Automatic config file generation

### Additional Features
- User authentication & authorization
- Dark/Light mode toggle
- Favorite commands
- Export/Import configurations
- Role-based access control (RBAC)
- Activity logging
- Real-time notifications
- Multi-vendor support

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- Docker & Docker Compose
- Git

### Using Docker Compose (Recommended)

```bash
# Clone the repository
git clone https://github.com/samtech1484-dev/network-operations-toolkit.git
cd network-operations-toolkit

# Copy environment file
cp .env.example .env

# Start the application
docker-compose up --build
```

Application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000
- NGINX Proxy: http://localhost:80

### Manual Setup

**Backend Setup:**
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

**Frontend Setup:**
```bash
cd frontend
npm install
npm start
```

## 📦 Technology Stack

### Frontend
- React 18, TypeScript, Tailwind CSS
- Axios, React Router, Zustand
- Chart.js, React Hot Toast

### Backend
- Node.js, Express.js, TypeScript
- MongoDB, JWT, Bcrypt
- Socket.io, SSH2

### DevOps
- Docker, Docker Compose
- NGINX, GitHub Actions

## 🔐 Security Features

- ✅ JWT-based authentication
- ✅ Encrypted credential storage
- ✅ Session timeout
- ✅ Input sanitization
- ✅ RBAC support
- ✅ Audit logging
- ✅ HTTPS/TLS support
- ✅ CORS configuration
- ✅ Rate limiting

## 📚 Documentation

- [Installation Guide](docs/INSTALLATION.md)
- [API Documentation](docs/API_DOCUMENTATION.md)
- [Database Schema](docs/DATABASE_SCHEMA.md)
- [Deployment Guide](docs/DEPLOYMENT.md)

## 📝 License

MIT License - see LICENSE file for details

---

**Built with ❤️ for Network Engineers**
