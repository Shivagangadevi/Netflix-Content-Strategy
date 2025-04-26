
# Netflix Content Strategy Analysis with Python

For the task of Netflix Content Strategy Analysis, we need data based on content titles, type (show or movie), genre, language, and release details (date, day of the week, season) to understand timing and content performance. Viewership metrics like hours viewed are also crucial for measuring audience engagement.

I found an ideal dataset for this task, which contains data about title, release date, language, content type (show or movie), availability status, and viewership hours of the content on Netflix of all the shows and movies released in 2023.

### Steps Followed

- Started by Importing the necessary python libraries and the load dataset into jupyter notebook.

- After loading the dataset, start anlyzing by as per business requirements.

- Analyzed trends in content type to determine whether shows or movies dominate viewership. The below visualization indicates that shows dominate the total viewership hours on Netflix in 2023 compared to movies. This suggests that Netflix’s content strategy leans heavily toward shows, as they tend to attract more watch hours overall.

![Image](https://github.com/user-attachments/assets/aa384ea7-4172-4d12-93f9-1bc5d0a9b617)

- Next analyzed the distribution of viewership across different languages to understand which languages are contributing the most to Netflix’s content consumption. The below visualization reveals that English-language content significantly dominates Netflix’s viewership, followed by other languages like Korean. It indicates that Netflix’s primary audience is consuming English content, although non-English shows and movies also have a considerable viewership share, which shows a diverse content strategy.

![Image](https://github.com/user-attachments/assets/841219b6-14ff-42ae-a024-0aba87c7ffc6)

- Next, analyzed how viewership varies based on release dates to identify any trends over time, such as seasonality or patterns around specific month. The below graph shows the total viewership hours by month, which reveals a notable increase in viewership during June and a sharp rise toward the end of the year in December.

![Image](https://github.com/user-attachments/assets/634d582d-d785-4364-9f59-4eefaeead108)

- To delve deeper, I Analyzed the most successful content (both shows and movies) and understand the specific characteristics, such as genre or theme, that may have contributed to high viewership.

- Next, analyzed how viewership trends by content type. The graph shows that shows consistently have higher viewership than movies, peaking in December. Movies have more fluctuating viewership, with notable increases in June and October. This indicates that Netflix’s audience engages more with shows across the year

![Image](https://github.com/user-attachments/assets/94f64648-6f88-4d7d-9c48-af344a50448e)

- Now, I've analyzed the total viewership hours distributed across different release seasons. The graph indicates that viewership hours peak significantly in the Fall season, with over 80 billion hours viewed, while Winter, Spring, and Summer each have relatively stable and similar viewership around the 20 billion mark. This suggests that Netflix experiences the highest audience engagement during the Fall.

![Image](https://github.com/user-attachments/assets/e3bcc9df-a349-49e1-92fe-04ba7ea1d942)

- Next, I've analyzed the number of content releases and their viewership hours across months. From the below graph we can say, while the number of releases is relatively steady throughout the year, viewership hours experience a sharp increase in June and a significant rise in December, despite a stable release count. This indicates that viewership is not solely dependent on the number of releases but influenced by the timing and appeal of specific content during these months.

![Image](https://github.com/user-attachments/assets/1a7c4408-1dec-4b55-bac0-f06e6aa8dc53)

- Now, analyzed whether Netflix has a preference for releasing content on specific weekdays and how this influences viewership patterns. The graph highlights that most content releases occur on Fridays, with viewership hours also peaking significantly on that day. This suggests that Netflix strategically releases content toward the weekend to maximize audience engagement. The viewership drops sharply on Saturdays and Sundays, despite some releases, indicating that the audience tends to consume newly released content right at the start of the weekend, which makes Friday the most impactful day for both releases and viewership.

![Image](https://github.com/user-attachments/assets/1edc2435-a315-482f-9855-81a24f684a02)


## Conclusion

So, the content strategy of Netflix revolves around maximizing viewership through targeted release timing and content variety. Shows consistently outperform movies in viewership, with significant spikes in December and June, indicating strategic releases around these periods. The Fall season stands out as the peak time for audience engagement. Most content is released on Fridays, which aims to capture viewers right before the weekend, and viewership aligns strongly with this release pattern. While the number of releases is steady throughout the year, viewership varies, which suggests a focus on high-impact titles and optimal release timing over sheer volume.
