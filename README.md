# FraudGuard Frontend

A modern, responsive web application for credit card fraud detection built with React, Vite, and Tailwind CSS.

## 🚀 Features

- **Single Transaction Analysis**: Analyze individual credit card transactions for fraud
- **Batch Processing**: Process multiple transactions simultaneously
- **Real-time Dashboard**: Monitor system health and performance
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI/UX**: Clean, professional interface with smooth animations
- **API Integration**: Seamlessly connects to the Flask backend API

## 🛠️ Tech Stack

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Heroicons (SVG)
- **Fonts**: Inter (Google Fonts)
- **State Management**: React Hooks
- **HTTP Client**: Fetch API

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Header.jsx      # Navigation header
│   ├── Hero.jsx        # Hero section
│   ├── SinglePrediction.jsx  # Single transaction form
│   ├── BatchPrediction.jsx   # Batch processing form
│   ├── Dashboard.jsx   # System dashboard
│   └── Footer.jsx      # Footer component
├── App.jsx             # Main application component
├── index.css           # Global styles and Tailwind imports
└── main.jsx           # Application entry point
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Running Flask backend API (http://localhost:5000)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd fraud-detection-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## 🎨 Design System

### Color Palette
- **Primary**: Blue-gray tones (#64748b, #475569)
- **Accent**: Red tones for alerts (#ef4444, #dc2626)
- **Neutral**: Gray scale (#f8fafc to #0f172a)
- **Success**: Green (#10b981)
- **Warning**: Yellow (#f59e0b)
- **Error**: Red (#ef4444)

### Typography
- **Primary Font**: Inter (sans-serif)
- **Monospace**: JetBrains Mono (for code)
- **Font Weights**: 300, 400, 500, 600, 700

### Components
- **Cards**: White background with subtle shadows and borders
- **Buttons**: Primary (blue) and secondary (gray) variants
- **Inputs**: Clean, focused states with validation
- **Status Indicators**: Color-coded badges and icons

## 🔌 API Integration

The frontend connects to the Flask backend API with the following endpoints:

- `GET /health` - Health check
- `GET /` - API information
- `GET /model_info` - Model details
- `GET /sample_data` - Sample transaction data
- `POST /predict` - Single transaction prediction
- `POST /predict_batch` - Batch transaction prediction

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-featured interface with side-by-side layouts
- **Tablet**: Adaptive layouts with optimized spacing
- **Mobile**: Stacked layouts with touch-friendly controls

## 🎯 Key Components

### SinglePrediction
- Form for individual transaction analysis
- Real-time validation and error handling
- Detailed results display with risk assessment
- Sample data generation for testing

### BatchPrediction
- Dynamic transaction form management
- Bulk processing capabilities
- Comprehensive results summary
- Error handling for individual transactions

### Dashboard
- System health monitoring
- Model information display
- Performance metrics
- API endpoint documentation

## 🚀 Performance Features

- **Lazy Loading**: Components load on demand
- **Optimized Images**: SVG icons for crisp display
- **Smooth Animations**: CSS transitions and keyframes
- **Efficient Rendering**: React optimization techniques

## 🔧 Customization

### Styling
Modify the design system in `tailwind.config.js`:
```javascript
theme: {
  extend: {
    colors: {
      primary: { /* Custom primary colors */ },
      accent: { /* Custom accent colors */ }
    }
  }
}
```

### Components
All components are modular and can be easily customized:
- Update colors and spacing in component files
- Modify Tailwind classes for different styles
- Add new features and functionality

## 🧪 Testing

The application includes comprehensive testing capabilities:
- **Manual Testing**: Interactive forms and real-time validation
- **API Testing**: Integration with backend endpoints
- **Responsive Testing**: Cross-device compatibility

## 📦 Deployment

### Build
```bash
npm run build
```

### Deploy
The built files can be deployed to any static hosting service:
- **Netlify**: Drag and drop the `dist/` folder
- **Vercel**: Connect your repository
- **AWS S3**: Upload the `dist/` contents
- **GitHub Pages**: Use the `dist/` folder

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions:
- Check the API documentation
- Review the component documentation
- Open an issue on GitHub

## 🔮 Future Enhancements

- **Real-time Updates**: WebSocket integration for live data
- **Advanced Analytics**: Charts and graphs for insights
- **User Authentication**: Login and user management
- **Dark Mode**: Toggle between light and dark themes
- **Internationalization**: Multi-language support
- **PWA Features**: Offline capabilities and app-like experience

---

Built with ❤️ using React, Vite, and Tailwind CSS
