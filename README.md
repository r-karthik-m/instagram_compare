# **Instagram Analytics Pro** 📊

A premium, feature-rich web application designed to analyze your Instagram followers and following lists with advanced statistics, insights, and export capabilities.

## **✨ Features**

### **Core Analysis**
* **Find Unfollowers** - See who you follow that doesn't follow you back
* **Find Fans** - Discover people who follow you that you don't follow back
* **Mutual Followers** - View your genuine connections (people who follow each other)
* **Privacy-Focused** - All processing happens in your browser. No data is sent to any server.

### **📈 Statistics Dashboard**
* Total following and followers count
* Mutual followers count and percentage
* Follow ratio (followers/following)
* Engagement rate visualization
* Mutual follow rate with progress bars
* Real-time metrics and insights

### **🎨 Premium Design**
* Modern glassmorphism UI with smooth animations
* Beautiful gradient backgrounds
* Responsive design (works on mobile, tablet, and desktop)
* Smooth micro-interactions and transitions
* Professional color palette with vibrant accents

### **🌓 Theme Support**
* Manual light/dark mode toggle
* Automatic system theme detection
* Persistent theme preference
* Smooth theme transitions

### **💾 Export Functionality**
* Export to **CSV** (Excel-compatible)
* Export to **JSON** (for developers)
* Export to **TXT** (simple text format)
* All data included with proper categorization

### **🔍 Search & Filter**
* Real-time search across all lists
* Alphabetical sorting (A-Z or Z-A)
* Instant filtering as you type
* Search highlights

### **📋 Quick Actions**
* Copy individual usernames with one click
* Copy entire lists to clipboard
* Direct links to Instagram profiles
* Batch operations support

### **💪 Enhanced UX**
* Drag-and-drop file upload
* File upload status indicators
* Loading states and animations
* Toast notifications for all actions
* Data persistence (auto-save/load)
* Clear data option for privacy
* Empty states with helpful messages
* Keyboard-friendly interface

## **🚀 How to Use**

### **Step 1: Get Your Instagram Data**

1. Go to your Instagram profile → **Settings** → **Your information and permissions** → **Download your information**
2. Request a download (select **JSON format**, not HTML)
3. Wait for Instagram to email you when your data is ready (this may take up to 48 hours)
4. Download and unzip the file

### **Step 2: Find the Required Files**

Navigate to the unzipped folder and locate:
```
followers_and_following/
  ├── followers.json
  └── following.json
```

### **Step 3: Use the Tool**

1. Open `instagram_compare.html` in any modern web browser (Chrome, Firefox, Edge, or Safari)
2. Upload your **following.json** file (click or drag-and-drop)
3. Upload your **followers.json** file (click or drag-and-drop)
4. Click **"🚀 Analyze Now"**

### **Step 4: Explore Your Results**

* View comprehensive statistics in the dashboard
* Switch between three tabs:
  - 👎 **Not Following Back** - People you follow who don't follow you
  - 🤷 **You Don't Follow** - People who follow you that you don't follow
  - 🤝 **Mutual Followers** - Your genuine connections
* Use the search bar to find specific usernames
* Export your data in your preferred format (CSV, JSON, or TXT)
* Copy usernames or entire lists with one click

## **📊 What You'll Learn**

* **Engagement Insights** - See what percentage of people you follow actually follow you back
* **Follow Ratio** - Understand your follower-to-following balance
* **Mutual Connections** - Identify your core community
* **Unfollowers** - Discover who unfollowed you or never followed back
* **Growth Opportunities** - Find followers you might want to connect with

## **🔒 Privacy & Security**

* ✅ **100% Client-Side** - All processing happens in your browser
* ✅ **No Server Upload** - Your data never leaves your computer
* ✅ **No Tracking** - We don't collect any analytics or user data
* ✅ **Open Source** - The code is transparent and auditable
* ✅ **Offline Capable** - Works without an internet connection after initial load
* ✅ **Clear Data Option** - Remove saved data anytime with one click

## **💡 Tips & Tricks**

* **Save Time** - Your last analysis is automatically saved and reloaded when you return
* **Export for Records** - Download your analysis to track changes over time
* **Use Search** - Quickly find specific usernames in large lists
* **Copy Lists** - Export lists to your clipboard for use in other tools
* **Dark Mode** - Toggle between light and dark themes for comfortable viewing
* **Mobile Friendly** - Access your analytics on any device

## **🎯 Best Practices**

1. **Compare Regularly** - Download your data monthly to track follower trends
2. **Export History** - Save exports to see who unfollowed you over time
3. **Be Selective** - Use the insights to curate a meaningful following
4. **Engage with Mutuals** - Focus on building relationships with people who follow you back
5. **Don't Overthink** - Remember, quality connections matter more than numbers

## **🛠️ Technical Details**

* **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
* **Styling**: Tailwind CSS via CDN
* **Font**: Inter (Google Fonts)
* **Storage**: localStorage for data persistence
* **Browser Support**: All modern browsers (Chrome, Firefox, Edge, Safari)
* **File Size**: Single HTML file (~50KB)
* **Performance**: Handles thousands of followers/following efficiently

## **🐛 Troubleshooting**

**Problem**: Files won't upload
* **Solution**: Ensure you're uploading the correct JSON files from the `followers_and_following` folder

**Problem**: Error parsing JSON
* **Solution**: Make sure you requested data in JSON format (not HTML) from Instagram

**Problem**: Results don't seem accurate
* **Solution**: Make sure both files are from the same data export

**Problem**: Data not saving
* **Solution**: Check if your browser allows localStorage (disable private/incognito mode)

## **📝 License**

This project is free to use for personal purposes. Feel free to modify and share!

## **🙏 Credits**

Created with ❤️ to help people better understand their Instagram connections.

---

**Remember**: Social media is about meaningful connections, not just numbers. Use this tool to build better relationships! 🤝
