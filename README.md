# Youtube_Channel_Growth_Analytics_20 CaseCraft Analytics Project Sprint Project 20

## 📺 Overview  
This project models YouTube channel growth using synthetic video performance data. It blends CTR analysis, clustering, regression modeling, and strategic visualizations to optimize content planning and subscriber acquisition.

## 🎯 Objective  
To analyze thumbnail CTR, engagement metrics, and content themes to predict subscriber gain and guide posting strategy.

## 📊 Dataset & Features  
- Videos: 300 synthetic entries  
- Features:  
  - Views, Likes, Comments  
  - CTR (Click-Through Rate)  
  - Subs Gained  
  - Theme: Tutorial, Vlog, Review, Challenge, Explainer  
  - Upload Day: Mon, Wed, Fri, Sun  
- Derived: Engagement (likes + comments)

## 📈 Visual Explorations  
- **Scatterplot**: CTR vs Subscriber Gain by Theme  
- **Boxplot**: Engagement by Upload Day  
- **KMeans Clustering**: Views vs CTR  
- **Bar Chart**: Avg Subs Gained by Theme  
- **Violin Plot**: CTR Distribution by Theme  
- **Scatterplot**: Engagement vs Views (log scale)  
- **Bar Chart**: Avg CTR by Upload Day  
- **Heatmap**: Correlation Matrix of Engagement Metrics

## 🔍 Modeling & Insights  
- **Regression Model**:  
  - Input: views, likes, comments, CTR, theme  
  - Target: subs_gained  
  - Model: Gradient Boosting Regressor  
  - Performance: MAE ≈ **1,340 subscribers**

## 🧠 Key Insights  
1. **CTR Power**: Strong predictor of subscriber gain, especially for Tutorial and Explainer videos  
2. **Upload Timing**: Friday and Sunday show higher CTR and engagement  
3. **Clustering Utility**: Reveals 4 performance zones based on views and CTR  
4. **Engagement Saturation**: Diminishing returns at high view counts  
5. **Theme Impact**: Tutorial and Vlog outperform Review in subscriber growth

## ✅ Final Conclusion  
YouTube channel growth is driven by thumbnail performance, content theme, and upload timing. This framework supports strategic planning, audience targeting, and predictive modeling—ideal for creators optimizing content cadence and subscriber acquisition.