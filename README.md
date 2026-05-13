# 🐔 Poultry Farm PMS - Preventive Maintenance System

A comprehensive React-based Preventive Maintenance System (PMS) designed for managing poultry farms' equipment maintenance schedules, tracking, and compliance monitoring.

## ✨ Features

- **Multi-Farm Management**: Monitor and manage up to 6 poultry farms from a single dashboard
- **Equipment Tracking**: Real-time tracking of equipment status (Due, Overdue, Completed)
- **Maintenance Dashboard**: Visual overview with key metrics
  - Due PMS count
  - Overdue PMS count
  - Completed maintenance this month
  - Compliance rate percentage
- **Equipment Monitoring Table**: Detailed view of all equipment with:
  - Equipment ID and Name
  - Category classification
  - Next PMS date
  - Assigned technician
  - Current status with color-coded badges
- **Critical Alerts**: Overdue maintenance warnings and alerts
- **Monthly Calendar**: Visual representation of scheduled maintenance
- **Equipment Management Forms**:
  - Add new equipment with details
  - Edit existing equipment records
  - Delete equipment from the system
- **Responsive Design**: Mobile-friendly interface using Tailwind CSS
- **Professional UI**: Modern, intuitive dashboard with smooth transitions

## 🛠️ Tech Stack

- **Frontend Framework**: React 18.2.0
- **Build Tool**: Vite 5.0.8
- **Styling**: Tailwind CSS 3.3.6
- **CSS Processing**: PostCSS + Autoprefixer

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup Steps

1. **Clone the repository**
```bash
git clone https://github.com/kjarovilla/GrandParentsStockOperationsMindanao.git
cd GrandParentsStockOperationsMindanao
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

4. **Open in browser**
```
http://localhost:5173
```

## 🚀 Building for Production

```bash
npm run build
```

This generates an optimized production build in the `dist/` folder.

## 📂 Project Structure

```
GrandParentsStockOperationsMindanao/
├── src/
│   ├── App.jsx           # Main PMS component
│   ├── main.jsx          # React entry point
│   └── index.css         # Tailwind styles
├── index.html            # HTML template
├── vite.config.js        # Vite configuration
├── tailwind.config.js    # Tailwind CSS config
├── postcss.config.js     # PostCSS config
├── package.json          # Dependencies
└── .gitignore            # Git ignore rules
```

## 📊 Dashboard Components

### Sidebar Navigation
- Dashboard
- Equipment
- PMS Schedule
- Overdue Tasks
- Reports
- Analytics
- Users
- Settings

### Main Content Area
1. **Header Section**: Title and farm selector
2. **Metrics Cards**: Quick stats display
3. **Equipment Table**: Searchable equipment list
4. **Overdue Alerts**: Critical maintenance warnings
5. **Monthly Overview**: Calendar-style schedule view
6. **Equipment Management**: Add/Edit/Delete forms

## 🎯 Sample Data

The application comes with pre-populated sample data for 6 farms:
- **Farm 1**: 12 due, 3 overdue, 44 completed (with 3 sample equipment)
- **Farm 2**: 5 due, 1 overdue, 32 completed
- **Farm 3**: 7 due, 0 overdue, 28 completed
- **Farm 4**: 9 due, 2 overdue, 35 completed
- **Farm 5**: 3 due, 0 overdue, 20 completed
- **Farm 6**: 11 due, 4 overdue, 41 completed

Sample Equipment (Farm 1):
- **GEN-001**: Generator 1 (Electrical) - Overdue
- **FAN-001**: Tunnel Fan 1 (Ventilation) - Due
- **ROT-001**: Rotem Smart Controller (Automation) - Completed

## 🎨 Color Scheme

- **Red**: Overdue maintenance (Critical)
- **Yellow**: Due maintenance (Warning)
- **Green**: Completed maintenance
- **Blue**: Navigation and actions
- **Dark Gray**: Sidebar and headers
- **Light Gray**: Background and cards

## 📱 Responsive Breakpoints

- **Mobile**: Single column layout
- **Tablet**: 2-column grid for metrics
- **Desktop**: Full multi-column dashboard layout

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## 📝 Notes

This is a frontend-only application. For full functionality with database integration, you would need:
- Backend API (Node.js/Express, Python/Django, etc.)
- Database (MongoDB, PostgreSQL, MySQL, etc.)
- Authentication system
- Real-time data sync

## 🚀 Deployment

### Vercel (Recommended)
```bash
npm run build
# Then deploy the dist/ folder to Vercel
```

### GitHub Pages
Follow GitHub Pages deployment guide for React + Vite projects.

## 👨‍💻 Author

**Kent Jarovilla**
- GitHub: [@kjarovilla](https://github.com/kjarovilla)
- Repository: [GrandParentsStockOperationsMindanao](https://github.com/kjarovilla/GrandParentsStockOperationsMindanao)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to fork and submit pull requests.

## 📞 Support

For issues and questions, please open an issue on the GitHub repository.

---

**Happy Farming! 🚜🐔**
