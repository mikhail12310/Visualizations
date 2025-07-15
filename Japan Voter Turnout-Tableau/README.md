# Japanese House of Councillors Voting Rate Dashboard

## Overview
This interactive Tableau dashboard visualizes voting rates across Japanese prefectures for House of Councillors elections from 1983 to 2022. The visualization demonstrates the use of dynamic color ranges to show temporal changes in voter participation across different regions of Japan.

## 🔗 Live Dashboard
[View the interactive dashboard on Tableau Public](https://public.tableau.com/shared/YMRPP2WXW?:display_count=n&:origin=viz_share_link)

## 📊 Features
- **Interactive Map**: Geographic visualization of Japan showing voting rates by prefecture
- **Temporal Analysis**: Data spanning nearly 40 years (1983-2022) of House of Councillors elections
- **Dynamic Color Ranges**: Color coding adapts to show relative voting rates for each time period
- **Year Filter**: Interactive timeline to explore voting patterns across different election cycles
- **Regional Filter**: Ability to focus on specific regions of Japan
- **Responsive Design**: Optimized for various screen sizes and devices

## 🎯 Key Insights
- **Geographic Patterns**: Visualizes regional differences in voter participation
- **Temporal Trends**: Shows how voting rates have changed over four decades
- **Comparative Analysis**: Enables comparison between different prefectures and time periods
- **Political Engagement**: Provides insights into civic participation across Japan

## 🛠️ Technical Implementation
### Data Structure
- **Time Dimension**: Election years from 1983-2022
- **Geographic Dimension**: Japanese prefectures with generated latitude/longitude coordinates
- **Measure**: Voting ratio percentage
- **Color Encoding**: Dynamic color ranges based on data distribution for each year

### Tableau Features Used
- **Map Visualization**: Geographic mapping with custom color scales
- **Calculated Fields**: Dynamic color range calculations
- **Filters**: Interactive year and region filtering
- **Parameters**: Dynamic color range parameters
- **Tooltips**: Contextual information on hover

## 📈 Data Sources
- Japanese House of Councillors election data
- Prefecture geographic coordinates
- Voting participation statistics by region and year

## 🎨 Design Choices
- **Color Palette**: Red-to-blue gradient for intuitive interpretation (low to high participation)
- **Geographic Accuracy**: Proper positioning of Japanese prefectures
- **Interactive Elements**: Filters positioned for easy access
- **Clean Layout**: Minimalist design focusing on data clarity

## 🔄 Updates and Maintenance
- Data is updated following each House of Councillors election (typically every 3 years)
- Color ranges automatically adjust based on data distribution
- Geographic boundaries remain consistent for temporal comparison

## 📱 Usage Instructions
1. **Navigate Years**: Use the year filter on the right to explore different election cycles
2. **Regional Focus**: Select specific regions using the region filter
3. **Detailed View**: Hover over prefectures to see exact voting percentages
4. **Color Interpretation**: Darker blue indicates higher voting rates, red indicates lower rates

## 🏆 Recognition
This dashboard was created as part of Workout Wednesday 2025 Week 28, focusing on the challenge: "Can you use Dynamic Color Ranges?"

## 📝 Notes
- Voting rates are calculated as percentage of eligible voters who participated
- Color ranges are dynamically calculated for each year to show relative performance
- Geographic boundaries reflect Japanese administrative divisions

## 🤝 Contributing
If you have suggestions for improvements or additional data sources, please feel free to reach out through Tableau Public or create an issue in the project repository.

## 📄 License
This visualization is shared publicly on Tableau Public for educational and analytical purposes.

---

**Author**: Yusuke Nakanishi  
**Platform**: Tableau Public  
**Last Updated**: 2025  
**Dashboard Type**: Interactive Geographic Visualization