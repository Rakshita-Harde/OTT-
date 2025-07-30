# OTT-

# 🎥 OTT-data
**📽️OTT Movies Data Analysis🍿**
- This project analyzes user behavior across different OTT platforms using a dataset of 5,000 entries. It uncovers trends related to watch time, genres, device usage, location, and content engagement to help OTT services improve their offerings and user experience.
  
**🚩 Summary**
- This project is about to analyse the user behaviour on various platforms on the bases of their intrest in different geners , rate of completion , whatch category , devices etc.

**👉 Dataset Features**
- **user_id :** Unique identifier for each user
- **platform :** Name of the streaming platform (e.g., Netflix, Hulu)
- **watch_time_minutes :** Total time user spent watching content (in minutes)
- **genre :** Genre of the content watched (e.g., Drama, Horror)
- **date :** Date when the content was watched
- **device :** Device used to watch content (e.g., Smart TV, Mobile)
- **location :**  Geographic location of the user
- **completion_rate :** Percentage of content watched (0 to 100%)
- **watch_category:** Category of viewing time (e.g., Short, Long sessions)
  
**⚙️Tools and Libraries Used**
- **Pandas –** Data manipulation and analysis
- **NumPy –** Mathematical operations
- **Matplotlib & Seaborn –** Data visualization
- **Jupyter Notebook –** Interactive analysis environment
  
**🪜 Steps**
**1. Data Import 🔃**
- Dataset was successfully loaded using the pandas library in Jupyter Notebook.
**2. Data Preparation 🔐**
- Converted date-related columns into datetime format for accurate time-based analysis.
**3. Exploratory Data Analysis (EDA) 📈📉**
- Counted the frequency of each device type (Smart TV: 870).
- Calculated the average completion rate for each platform.
- Identified and listed content in order of increasing completion rate.
**4. Data Visualization 📊**
- Histogram: Analyzed the distribution of the completion_rate and watch_time_minutes variables.
- Heatmap: Explored correlations, especially between watch time and completion rate.
- Histplot: Visualized the frequency of watchtime distributon .
  
**✅ Strategic Recommendations**
**1. Enhance Experience on Smart TVs and Tablets 📺**
**Observation:** Users watching through Smart TVs and Tablets log the highest average watch durations.
**Action:** Prioritize feature rollouts (e.g., autoplay, resume playback, personalized carousels) for these platforms to keep users engaged longer.
**2. Completion Rate Gaps Across Platforms ⏳**
**Observation:** Services like Netflix exhibit higher completion rates, while mobile web and browser-based apps lag behind.
**Action:** Investigate underperforming platforms for potential usability issues (e.g., buffering, poor interface). Utilize user feedback or session replay tools to identify causes of early exits.
**3. Capitalize on Long Horror Content Performance 👻**
**Observation:** Long-form horror shows and movies attract extensive watch time.
**Action:** Expand offerings in this genre. Curate themed playlists like horror marathons or time-limited series to further boost viewership.
**4. Improve Retention for Short Content ❌**
**Observation:** Short videos (<5 mins) are still suffering from low completion, likely due to weak starts or mismatched recommendations.
**Action:** Implement features like “Auto-next” or organize short clips into seamless playlists to enhance continuity and engagement.
