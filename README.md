# 🌉 Bridge Days Calculator

A smart web application that helps you maximize your vacation time by finding the best "bridge days" - strategic vacation days that, when combined with public holidays and weekends, give you the most consecutive days off for the least amount of vacation time.

## ✨ Features

- **Smart Bridge Detection**: Automatically finds the most efficient vacation opportunities
- **Global Holiday Support**: Uses the OpenHolidays API for accurate public holiday data across countries
- **Visual Calendar**: Interactive calendar showing holidays, bridge days, and vacation opportunities
- **Efficiency Rating**: Shows how many total days off you get per vacation day taken
- **Customizable Work Schedule**: Configure which days of the week you work
- **Week Start Preference**: Choose between Monday or Sunday week start
- **Regional Support**: Select specific regions/subdivisions for more accurate holiday data
- **Responsive Design**: Works on desktop and mobile devices

## 🚀 Live Demo

Visit **[bridgedays.github.io](https://bridgedays.github.io)** to try it out!

## 📖 How to Use

1. **Select Your Country**: Choose your country from the dropdown
2. **Pick Region** (optional): Select your specific state/region for regional holidays
3. **Set Year**: Choose the year you're planning for
4. **Configure Work Days**: Check/uncheck which days you normally work
5. **Set Week Start**: Choose if your week starts on Monday or Sunday
6. **View Opportunities**: The app will automatically show bridge day opportunities ranked by efficiency

### Reading the Results

- **Red highlighted days**: Vacation days you need to take
- **Green highlighted days**: Public holidays (free days off)
- **Blue borders**: Extended vacation period including weekends
- **Efficiency ratio**: Shows vacation days needed / total days off gained

## 🛠️ Tech Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **API**: [OpenHolidays API](https://openholidaysapi.org) for holiday data
- **Hosting**: GitHub Pages

## 📁 Project Structure

```
├── index.html          # Main application file
├── openholiday.json    # API documentation
└── README.md          # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs by opening an issue
- Suggest new features
- Submit pull requests

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [OpenHolidays API](https://openholidaysapi.org) for providing free, accurate holiday data
- Built with ✨ and Claude AI assistance

---

**Happy vacation planning!** 🏖️
