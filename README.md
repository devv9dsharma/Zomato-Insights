# Zomato Insights - Power BI Dashboard

**Zomato Insights** is a Power BI dashboard that leverages the Zomato API to provide interactive, self-service analytics on restaurant trends, ratings, and cuisine popularity across multiple cities.

---

## 📊 Features

- **Interactive Reports**: Filter data by city, cuisine, and ratings using slicers and bookmarks.
- **Drill-through Pages**: Click on summary visuals to explore detailed restaurant or area views.
- **Geospatial Analysis**: Visual maps showing restaurant locations and density by city.
- **Time-Based Trends**: Monthly breakdowns of restaurant openings, reviews, and pricing trends.
- **Custom KPIs**: Track restaurant counts, average ratings, review volumes, and cost metrics.

---

## 🔌 Data Sources

- **Zomato Public API**  
  Provides access to:
  - Restaurant metadata
  - Ratings and reviews
  - Location and cuisine info

- **API Endpoints Used**:
  - `/search`
  - `/restaurant`
  - `/cuisines`

> Note: Requires Zomato API Key (register at [Zomato Developers](https://developers.zomato.com)).

---

## 🛠️ Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (64-bit recommended)
- Zomato API Key
- Internet connection for live API calls

---

## ⚙️ Setup Instructions

1. Clone or download this repository.
2. Open `Zomato_Insights.pbix` in Power BI Desktop.
3. Go to **Transform Data > Data Source Settings**, and add your Zomato API key (`user-key`).
4. Apply changes to load and visualize the data.

---

## 🧭 Dashboard Pages

1. **Home** – Overview of cities, ratings, and top cuisines
2. **Rating Analysis** – Ratings by restaurant and category
3. **Cuisine Insights** – Popular cuisines and trends
4. **Monthly Trends** – Time-based analysis of reviews, prices, etc.

---

## 🔧 Customization

- **Add Metrics**: Create DAX measures (e.g., average delivery time, sentiment scores).
- **API Expansion**: Include more endpoints such as `/daily_menu`.
- **Visual Tuning**: Modify visuals using the Visualizations pane for custom themes.

---

## 🚀 Usage Tips

- Click **Refresh** on the Home tab to fetch the latest API data.
- Use **City** parameter to switch between local market dashboards.
- Publish to Power BI Service for scheduled refresh and collaboration.

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes
4. Submit a Pull Request with clear explanation

---

## 📄 License

This project uses data from Zomato under their [API Terms of Use](https://developers.zomato.com/documentation). All visualizations and code are provided under the MIT License.

---

## 📬 Contact

For issues, suggestions, or feature requests:
- Open an issue on GitHub
- Email: **data-team@example.com**

---

## 🙏 Acknowledgments

- [Zomato Developer Platform](https://developers.zomato.com) for API access
- [Microsoft Power BI Docs](https://docs.microsoft.com/en-us/power-bi/) for visualization best practices
