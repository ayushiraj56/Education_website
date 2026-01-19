# EduHub - Online Learning Platform

A comprehensive education website built with HTML, CSS, JavaScript, and PHP that provides video lectures, live classes, study notes, and course management.

## 🚀 Quick Start (No Server Required)

### Option 1: Simple HTML Version (Recommended for Testing)

1. **Download all files** to a folder on your computer
2. **Load demo data**: Open `demo-data.html` in your browser and click "Load Demo Data"
3. **View website**: Open `index.html` in your browser
4. **Access admin**: Click "Admin Panel" or open `admin/dashboard.html`

### Option 2: Full PHP Version (For Production)

1. **Install XAMPP**: Download from [https://www.apachefriends.org/](https://www.apachefriends.org/)
2. **Start services**: Open XAMPP Control Panel, start Apache and MySQL
3. **Copy files**: Place all files in `C:\xampp\htdocs\eduhub\`
4. **Access website**: Go to `http://localhost/eduhub/index.html`
5. **Admin login**: Go to `http://localhost/eduhub/admin/login.php`
   - Username: `admin`
   - Password: `admin123`

## 📋 Features

### Student Features
- **Course Catalog**: Browse available courses with detailed information
- **Video Lectures**: Watch high-quality recorded video lectures
- **Live Classes**: Join interactive live sessions with instructors
- **Study Notes**: Download comprehensive study materials
- **Responsive Design**: Works seamlessly on desktop and mobile devices

### Admin Features
- **Course Management**: Add, edit, and delete courses
- **Video Upload**: Upload and manage video lectures
- **Live Class Scheduling**: Schedule and manage live classes with meeting links
- **Notes Management**: Upload and organize study materials
- **Dashboard**: Overview of platform statistics and recent activity

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: PHP 7.4+ (optional)
- **Database**: MySQL (optional)
- **Storage**: LocalStorage (for HTML version) or Database (for PHP version)
- **Styling**: Custom CSS with responsive design
- **Icons**: Font Awesome 6.0

## 📁 File Structure

```
eduhub/
├── index.html              # Main homepage
├── demo-data.html          # Load sample data
├── setup.html              # Setup instructions
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── script.js          # Frontend JavaScript
├── admin/                 # Admin panel
│   ├── dashboard.html     # HTML admin dashboard
│   ├── courses.html       # Course management
│   ├── live_classes.html  # Live class management
│   ├── notes.html         # Notes management
│   ├── videos.html        # Video management
│   ├── login.php          # PHP admin login
│   ├── dashboard.php      # PHP admin dashboard
│   └── css/
│       └── admin.css      # Admin panel styles
├── api/                   # API endpoints (PHP)
├── config/                # Database configuration (PHP)
└── uploads/               # File uploads (PHP)
```

## 🎯 How to Use

### For Students
1. Visit the homepage to browse courses and content
2. Navigate through different sections using the menu
3. Watch videos by clicking the "Watch" button
4. Download notes by clicking the "Download" button
5. Join live classes when they're active

### For Administrators

#### HTML Version:
1. Open `admin/dashboard.html` in your browser
2. Use the sidebar to navigate between sections
3. Add courses, schedule live classes, upload videos and notes
4. All data is stored in browser's localStorage

#### PHP Version:
1. Login at `/admin/login.php` with admin/admin123
2. Use the dashboard to get an overview of the platform
3. Add courses, schedule live classes, upload videos and notes
4. All data is stored in MySQL database

## 🔧 Troubleshooting

### Common Issues:

**Login page downloads instead of opening:**
- You need a web server to run PHP files
- Use XAMPP or similar server software
- Or use the HTML version (`admin/dashboard.html`)

**No content showing:**
- Load demo data using `demo-data.html`
- Or add content through the admin panel

**Files not uploading (PHP version):**
- Check file permissions on uploads folder
- Ensure Apache and MySQL are running
- Check PHP file upload limits

**Database connection errors:**
- Make sure MySQL is running in XAMPP
- Check database credentials in `config/database.php`
- Database will be created automatically on first run

## 🌟 Features in Detail

### Video Management
- Upload MP4, AVI, MOV, WMV files
- Automatic file size tracking
- View count tracking
- Modal video player for seamless viewing

### Live Classes
- Schedule classes with start/end times
- Integration with meeting platforms (Zoom, Google Meet)
- Real-time status indicators (Upcoming, Live, Completed)
- Direct join links for active classes

### Notes System
- Support for PDF, DOC, DOCX, TXT files
- Download tracking
- File size optimization
- Organized by upload date

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimized
- Touch-friendly interface
- Hamburger menu for mobile navigation

## 🔒 Security Features

- Password hashing for admin accounts (PHP version)
- SQL injection prevention with prepared statements
- File type validation for uploads
- Session management for admin authentication
- XSS protection with input sanitization

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile Features

- Responsive design works on all screen sizes
- Touch-friendly interface
- Mobile-optimized video player
- Swipe-friendly navigation

## 🚀 Deployment Options

### Local Development:
- Use XAMPP/WAMP for PHP version
- Or simply open HTML files in browser

### Web Hosting:
- Upload files to any web hosting service
- Ensure PHP 7.4+ and MySQL support
- Set proper file permissions

### Cloud Deployment:
- Works on AWS, Google Cloud, Azure
- Use managed database services
- Configure file storage for uploads

## 📈 Future Enhancements

- Student registration and authentication
- Progress tracking and certificates
- Discussion forums
- Assignment submissions
- Payment integration
- Mobile app development
- Advanced analytics dashboard
- Multi-language support

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 📞 Support

For support and questions:
- Check this documentation
- Review the code comments
- Test with the demo data
- Use the HTML version for quick testing

---

**Quick Start Summary:**
1. Open `demo-data.html` → Click "Load Demo Data"
2. Open `index.html` → Browse the website
3. Open `admin/dashboard.html` → Manage content

**For PHP version:** Use XAMPP and access via `http://localhost/eduhub/`