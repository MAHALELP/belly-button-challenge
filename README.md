
Belly Button Biodiversity Dashboard

Welcome to the Belly Button Biodiversity Dashboard! This project offers an engaging platform to delve into the intricate world of belly button samples. By harnessing the power of the D3 library, it effortlessly retrieves data from a JSON file and beautifully visualizes it using Plotly.js.

Steps to Navigate the Dashboard

Data Retrieval: Leveraging the robust capabilities of the D3 library, the dashboard seamlessly fetches data from the designated URL(https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json).

Horizontal Bar Chart: Explore the top 10 Operational Taxonomic Units (OTUs) found in the selected individual through an intuitive horizontal bar chart. Witness the abundance of each unit with sample_values as the values, while the OTU IDs (otu_ids) serve as informative labels, and the hovertext (otu_labels) provides additional insights.

Bubble Chart: Immerse yourself in the diversity of each sample with a captivating bubble chart. Marvel at the distribution of OTUs using otu_ids for the x-axis, observe sample_values for the y-axis, and visualize the relative abundance with dynamic marker sizes. The colors of the markers, derived from the OTU IDs, enhance the visual experience, while the text values (otu_labels) offer a deeper understanding of each sample.

Sample Metadata Display: Delve into the intricate details of each sample's metadata, including demographic information. Every key-value pair from the metadata JSON object is meticulously looped through to craft a comprehensive text string, seamlessly appended as an HTML tag to the #sample-metadata panel.

Chart Updates: Witness the magic of dynamic exploration as all plots elegantly update with each new sample selection. Whether you're delving deeper into the dataset or discovering new insights, the dashboard ensures a seamless and engaging experience throughout your journey.

Embark on your exploration of belly button biodiversity with confidence, knowing that every aspect of the dashboard has been meticulously designed to offer both functionality and aesthetic appeal. Happy exploring!