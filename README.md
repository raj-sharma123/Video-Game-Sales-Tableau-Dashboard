# **🎮 Video Game Sales Analysis Report**

## **📌 Introduction**

This report analyzes global video game sales from a dataset of over 16,000 titles. Using Tableau dashboards, we uncover trends in platform performance, genre popularity, top-selling games, publisher strength, and regional sales behavior to better understand market dynamics and consumer behavior in the gaming industry.

**Tool**: Tableau

**Dataset Source Link**: https://www.kaggle.com/datasets/gregorut/videogamesales/data

## **🧾 Dataset Overview**

| Field         | Description                                   |
| ------------- | --------------------------------------------- |
| Name          | Title of the video game                       |
| Platform      | Platform the game was released on (e.g., PS2) |
| Year          | Release year                                  |
| Genre         | Game genre (e.g., Action, Sports)             |
| Publisher     | Game publisher (e.g., Nintendo, EA)           |
| NA\_Sales     | North America sales (in millions)             |
| EU\_Sales     | Europe sales (in millions)                    |
| JP\_Sales     | Japan sales (in millions)                     |
| Other\_Sales  | Sales in other regions                        |
| Global\_Sales | Total worldwide sales (sum of all regions)    |

---

## 📊 Dashboard Summary

Created **two insightful Tableau dashboards**, each focusing on different perspectives:


## 📍 **Dashboard 1: Global Overview of Sales Performance**

**Dashboard 1:** [Link](https://public.tableau.com/app/profile/raj.sharma123/viz/VideoGameSales_17478699584670/Dashboard1)

![Screenshot 2025-05-22 053144](https://github.com/user-attachments/assets/99dc4c96-984c-4ef8-b97f-7a4cbd0e35e0)

#### ✅ Key Visuals:

* **Sales Trend Over Time** (Line Chart)
* **Top Games by Global Sales** (Bar Chart)
* **Sales by Genre** (Bar Chart)
* **Top Publisher Performance** (Bar Chart)

#### 📈 Insights:

1. **Sales Trend Over Time**

   * Global sales peaked **between 2006 and 2010**, aligning with the release of Wii, Xbox 360, and PS3.
   * Post-2012, sales dropped significantly — likely due to a transition to **digital game distribution**, which isn't captured in this dataset.

2. **Top Games Globally**

   * *Wii Sports* is the top-selling title with **82.74M units**, benefiting from being bundled with the Wii console.
   * Other high performers: *GTA V*, *Super Mario Bros.*, *Tetris*, and *Mario Kart Wii*.
   * Nintendo holds **7 of the top 10 spots**, showing its dominance in first-party titles.

3. **Genre Sales**

   * **Action** is the most profitable genre with **1,751M units**, followed by **Sports (1,331M)** and **Shooter (1,037M)**.
   * These genres appeal to broad global audiences and often have long-running franchises.

4. **Publisher Performance**

   * **Nintendo** leads with **1,787M units sold**, far ahead of EA (1,110M) and Activision (727M).
   * Publisher success is heavily tied to exclusive IPs and platform control.

---

## 📍 **Dashboard 2: Platform & Regional Sales Analysis**

**Dashboard 2:** [Link](https://public.tableau.com/app/profile/raj.sharma123/viz/VideoGameSales2_17478704905790/Dashboard2)

![Screenshot 2025-05-22 053229](https://github.com/user-attachments/assets/354ed190-bc30-4618-88fd-d3b0e00e6d86)


#### ✅ Key Visuals:

* **Sales by Platform** (Treemap)
* **Regional Sales Comparison** (Stacked Bar Charts by Genre)
* **% of Sales by Genre** (Pie Chart)

#### 🌍 Insights:

1. **Platform Sales Performance**

   * **PS2** is the top-selling platform with **1,256M units**, followed closely by **X360, PS3, DS, Wii**, and **PS**.
   * Platforms with longer life cycles and large libraries tend to perform better globally.

2. **Regional Preferences**

   * **North America (NA)**:

     * Dominated by **Action**, **Shooter**, and **Sports** genres.
     * Total NA sales exceed 877M, with Action alone contributing 410M+.
   * **Japan (JP)**:

     * Strong preference for **Role-Playing Games (RPGs)**, with 352M in sales.
     * Shooter and Sports genres perform relatively poorly.
   * **Europe (EU)**:

     * Balanced genre distribution; Action and Sports top, with decent sales in Racing and RPGs.
   * **Other Regions**:

     * Smaller in volume but similar pattern to NA.

3. **Genre Share**

   * **Top genres globally by percentage**:

     * Action: \~19.6%
     * Sports: \~14.9%
     * Shooter: \~11.6%
     * Role-Playing: \~10.4%
   * Niche genres like Strategy and Puzzle have limited global reach.

---

## 📌 Business & Market Implications

| Area                      | Insights                                                                                                              |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Product Strategy**      | Invest in **Action**, **Sports**, and **Shooter** genres for global reach. Target **RPGs** for Japan.                 |
| **Publishing**            | Leverage first-party publishing like Nintendo; maintain tight control over IP.                                        |
| **Platform Development**  | Prioritize long-term support for platforms; strong libraries drive lifetime value.                                    |
| **Regional Marketing**    | Adapt game launches and marketing messages by region based on genre preferences.                                      |
| **Future Considerations** | Modern trends such as mobile gaming and digital distribution are not captured — future analysis should include those. |

## ✅ Conclusion

This analysis provides a deep look into how video game sales evolved over time, which platforms and publishers succeeded, and how different regions prefer different genres. By understanding these patterns, game developers and publishers can make informed decisions about market targeting, platform development, and genre investment.
