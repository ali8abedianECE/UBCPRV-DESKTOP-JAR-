# UBC Professor Visualizer

A standalone Java application that lets UBC students explore professor ratings and historical grade distributions in an interactive scatter-plot visualization.

## 📝 About

As a UBC student, I often struggled to find comprehensive information on professors and courses in one place. After learning Java fundamentals in CPEN 221, I was inspired to build this tool to help fellow students make well-informed course selection decisions by combining data from multiple sources into a single, interactive interface.

## ✨ Features

- **Comprehensive Data Integration**
  - Grade Distributions - fetches historical data from UBCGrades
  - Professor Ratings - pulls ratings & reviews from RateMyProfessors
  
- **Interactive Visualization**
  - Dynamic Scatter Plot - compare any two metrics (e.g., overall rating vs. percentage of A grades)
  - Zoom & Pan controls - explore data points in detail
  - Tooltips - view detailed information by hovering over data points
  
- **Powerful Filtering Options**
  - Filter by course code (e.g., CPEN 221)
  - Filter by faculty or department
  - Filter by rating range
  - Combine multiple filters for precise results

## 🔧 Requirements

- Java 8 or newer
- Internet connection (for fetching latest data)

## 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mohammadaliabedian/UBCPRV.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd UBCPRV
   ```

## 🚀 Usage

Run the application with:

```bash
java -jar UBCPRV.jar
```

## 🔍 How It Works

The application fetches data from multiple sources:
- Historical grade distributions from UBCGrades API
- Professor ratings and reviews from RateMyProfessors
- Combines this data into an interactive visualization where you can discover trends and make informed decisions

## 🛠️ Technologies Used

- Java (Core application)
- JavaFX (UI components)
- External APIs (UBCGrades, RateMyProfessors)

## 👥 Contributing

Contributions are welcome! If you'd like to improve the UBC Professor Visualizer:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- UBC CPEN 221 course for providing the foundational Java knowledge
- UBCGrades for providing historical grade data
- RateMyProfessors for professor rating information

## 📞 Support

If you encounter any issues or have questions, please [open an issue](https://github.com/mohammadaliabedian/UBCPRV/issues) on the GitHub repository.