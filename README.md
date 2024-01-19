# CS210project

In this data analysis project, I focused on exploring and visualizing email communication patterns using a dataset of emails sent and received. The project was divided into several key steps, including data export, organization, sentiment analysis, network analysis, and visualization.

1. Data Export and Organization:
The initial step involved exporting email data from the email client. I organized the exported data, obtained in MBOX format, into a structured format using Python. Key columns, such as Sender, Recipient, Date, Subject, and Content, were identified for further analysis.

2. Sentiment Analysis:
I performed sentiment analysis on the email content to understand the emotional tone of the communication. Natural Language Processing (NLP) techniques were employed to analyze the text and quantify the sentiment. This analysis provided insights into the overall mood of the emails, highlighting positive and negative sentiments.

3. Network Analysis:
To visualize relationships between different senders and recipients, I conducted a network analysis using the networkx library in Python. The resulting directed graph represented nodes as email addresses and edges as email interactions. This graph visualization offered a comprehensive view of the email network, revealing patterns of communication and highlighting key nodes in the network.

4. Time Series and Histogram Visualizations:
Temporal patterns in email communication were explored through time series and histogram visualizations. Daily and monthly email activity was plotted to identify trends and patterns over time. These visualizations helped uncover insights into peak communication periods and overall email frequency.

5. Word Clouds:
I generated word clouds for both email subjects and content. These visualizations provided a snapshot of the most frequently used words, offering a quick and intuitive understanding of the key themes in the email dataset. Word clouds served as a valuable tool for identifying common topics and trends within the communication.

6. Machine Learning for Prediction:
I applied a machine learning approach to predict email sender information based on email content. A Random Forest classifier was trained using TF-IDF vectorization of the content. This predictive model demonstrated the potential to automate sender identification in future emails.

7. Conclusion and Actionable Insights:
The analysis and visualizations yielded valuable insights into email communication within the dataset. Positive and negative sentiment trends were identified, and the network analysis showcased the structure of communication relationships. The time series plots revealed patterns of email activity over time, while word clouds highlighted key themes. The machine learning model presented a potential avenue for automating sender prediction.

The actionable insights derived from this analysis include strategies for improving communication, addressing sentiment trends, and optimizing email content based on identified themes. The network analysis can guide efforts to strengthen communication ties and enhance collaboration among different nodes in the network.

