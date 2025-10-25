# ⚽ Field Webbo - Mini Football Field Booking

A professional, responsive website for mini football field bookings with integrated WhatsApp and email communication.

## 🎯 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **WhatsApp Integration** - Direct booking via WhatsApp with formatted messages
- **Email Booking** - Professional email templates for booking requests
- **Two-Page System** - Marketing page + dedicated booking flow
- **Real-time Validation** - Form validation with visual feedback
- **Session Transfer** - Seamless data transfer between pages
- **Professional UI** - Modern design with smooth animations

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm (v8 or higher)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rakuten4/Football.git
   cd Football
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open in browser**
   - The website will automatically open at `http://localhost:3000`

## 📱 Contact Integration

### WhatsApp Setup
- **Number**: +234 816 947 2068
- **Auto-formatted messages** with booking details
- **Direct link integration** for instant communication

### Email Setup
- **Admin Email**: aderinkoyeemmanuel@gmail.com
- **Professional templates** with structured booking information
- **Mailto integration** for immediate email client opening

## 🛠️ Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Start development server on port 3000 |
| `npm run dev` | Start live-reload development server |
| `npm run build` | Validate and build project |
| `npm run validate` | Validate HTML files |
| `npm run lint` | Lint JavaScript files |
| `npm run format` | Format HTML, CSS, and JS files |
| `npm run deploy` | Prepare for deployment |

## 📁 Project Structure

```
field-webbo/
├── index.html          # Main marketing page
├── booking.html        # Dedicated booking page
├── images/            # Image assets
│   ├── 7-a-side-football.jpg
│   └── winterball.jpg
├── package.json       # Project dependencies
├── .gitignore        # Git ignore rules
└── README.md         # This file
```

## 🎨 Design Features

### Main Page (index.html)
- **Hero section** with custom background image
- **Features showcase** with 6 key selling points
- **Pricing section** clearly displaying $45/session
- **Booking form** that transfers data to booking page
- **Social media integration** (WhatsApp + TikTok)

### Booking Page (booking.html)
- **3-step process indicator**
- **Pre-filled form** from main page data
- **Real-time booking summary**
- **Dual submission options** (WhatsApp/Email)
- **Professional confirmation modals**

## 🔧 Configuration

### Customization Points

1. **Contact Information**
   ```javascript
   // In both HTML files
   const CONTACT_CONFIG = {
       whatsappNumber: '+2348169472068',
       adminEmail: 'aderinkoyeemmanuel@gmail.com'
   };
   ```

2. **Pricing**
   ```html
   <!-- Update in both files -->
   <div class="price">$45</div>
   ```

3. **Images**
   ```css
   /* Hero background */
   background: url('images/7-a-side-football.jpg') center/cover;
   
   /* Logo */
   background-image: url('images/winterball.jpg');
   ```

## 🌐 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Website will be available at: `https://rakuten4.github.io/Football/`

### Other Hosting Services
- **Netlify**: Drag and drop the project folder
- **Vercel**: Connect GitHub repository
- **Traditional Hosting**: Upload files via FTP

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Security Notes

- No sensitive data stored in frontend code
- Uses sessionStorage for temporary data transfer
- WhatsApp/Email integration for secure communication
- Form validation prevents malicious input

## 📞 Contact & Support

- **WhatsApp**: +234 816 947 2068
- **Email**: aderinkoyeemmanuel@gmail.com
- **GitHub**: [Rakuten4/Football](https://github.com/Rakuten4/Football)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🎯 Future Enhancements

- [ ] Payment gateway integration
- [ ] Admin dashboard for booking management
- [ ] Calendar availability system
- [ ] SMS notifications
- [ ] Multi-language support
- [ ] Customer review system

---

**Made with ⚽ for football enthusiasts**