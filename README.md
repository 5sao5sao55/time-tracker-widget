# TimeTracker Widget

Vietnamese time tracking widget for monitoring work tasks with Excel export functionality.

## Features

✨ **Core Features:**
- ⏱️ **Timer Tracking** - Start/stop timer with real-time display
- 📋 **Task Categories** - Pre-configured work categories
- 🏷️ **Quick Details** - Context-specific subtasks with one-click selection
- 📊 **Work Classification** - Fixed, ad-hoc, and support work types
- 📈 **Status Tracking** - Multiple status options (completed, planned, pending approval, etc.)
- 💾 **Local Storage** - All data persists automatically
- 📅 **Daily History** - View all tracked tasks for the day
- 📥 **Excel Export** - Generate formatted reports with summaries
- 🎹 **Keyboard Shortcuts** - Press Space to start/stop timer

## Quick Start

1. Open `index.html` in a web browser
2. Select a task category from the dropdown
3. Click quick detail tags or enter custom description
4. Choose work type and status
5. Click **Bắt đầu** (Start) button or press **Space**
6. Click **Kết thúc** (Stop) button or press **Space** to end the session
7. Export to Excel when done

## Usage

### Categories
- Thiết kế TRANH ĐIỆN - KV OUTSIDE
- Thiết kế KHU DÁN KÍNH BÊN NGOÀI
- Thiết kế bộ Zalo của Fruits T&T
- Sửa KV Buffet Sầu Riêng
- KV Buffet Sầu Riêng Ads Facebook
- Fill tag Trái cây
- Retouch ảnh
- Menu Bunny
- Buffet sầu riêng Fruits
- Nghỉ phép

### Work Types
- **Cố định** (Fixed)
- **Phát sinh** (Ad-hoc)
- **Hỗ trợ** (Support)

### Status Options
- Hoàn thành (Completed)
- Đang trong kế hoạch (Planned)
- Chờ duyệt cấp trên (Pending Approval)
- Hủy/Dời (Cancelled/Postponed)
- Trễ hạn (Overdue)
- Chờ tt bp liên quan (Awaiting Related Department)

## Data Export

### Excel File Format
The exported file includes:
- **Báo cáo ngày** (Daily Report) - Detailed task list with times and duration
- **Tổng hợp** (Summary) - Employee info, task counts, and status breakdown

### Exported Data Includes
- Time range (start/end times)
- Task category and details
- Work type and status
- Duration (both HH:MM:SS and decimal hours)
- Work results/notes
- Monthly summary statistics

## Browser Support
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers with localStorage support

## Technologies
- HTML5
- CSS3 (Flexbox, Gradient, Mobile-responsive)
- Vanilla JavaScript
- LocalStorage API
- XLSX.js for Excel generation

## Features Breakdown

### Storage
- Uses browser localStorage for persistence
- Data survives page refreshes
- Automatic daily reset logic available

### Export Format
- Compatible with Excel and Google Sheets
- Formatted with column widths
- Summary statistics included
- Pre-filled employee info

### Accessibility
- Vietnamese localization
- Responsive design (mobile-friendly)
- Keyboard shortcuts
- Clear visual feedback

## Developer Info

No dependencies required - runs entirely in the browser!

### Customization

Edit the `detailsMap` object in the script to:
- Add/remove work categories
- Update quick detail options
- Modify pre-filled summary info

```javascript
const detailsMap = {
    'Your Category': ['Detail 1', 'Detail 2', 'Detail 3']
};
```

## File Structure
```
time-tracker-widget/
├── index.html          # Main application
├── README.md           # This file
└── LICENSE             # MIT License
```

## License
MIT License - Feel free to use and modify for your needs

## Author
Created for efficient work tracking and reporting

---

**Last Updated:** 2026-05-26
