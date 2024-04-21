 Project Description: Data Cleaning for SKU Dataset in Bangladesh

 Overview
This repository details the data cleaning process implemented on a dataset containing approximately 90,000 stock keeping units (SKUs) relevant to the consumer goods industry in Bangladesh. This project marks a pioneering approach to digital data collection in the country, enhancing the data's usability for further analysis and decision-making processes. The dataset includes various attributes of SKUs such as category codes, brand codes, combined category and brand, category names, brands, variants, pack sizes, volumes, units, and packaging types.

 Data Privacy
To demonstrate the data cleaning techniques while maintaining data privacy, a subset of over 600 SKUs has been used in the examples provided in this repository. This subset represents the diversity and complexity of the entire dataset but ensures confidentiality and compliance with data protection regulations.

 Data Cleaning Process
The cleaning of this extensive dataset involved multiple stages, utilizing various data manipulation techniques to enhance data quality and structure, making it suitable for analysis. The key steps in the data cleaning process included:

1. Text to Columns:
   - Utilized to split combined information into separate columns for more precise analysis and accessibility. For example, separating combined category and brand information into distinct columns.

2. Pivot Tables:
   - Employed to summarize, reorganize, and aggregate data, helping in the detection of anomalies and inconsistencies. Pivot tables were pivotal in understanding the distribution and aggregation of data across different categories and brands.

3. VLOOKUP:
   - Used for merging and aligning data from different sources based on common columns. This function assisted in filling missing values and verifying data accuracy across the dataset.

4. TRIM, PROPER, UPPER, and LOWER Functions:
   - These text functions were crucial in normalizing textual data. `TRIM` was used to remove extra spaces; `PROPER` to capitalize the first letter of each word for standardization; `UPPER` and `LOWER` ensured that all entries followed a consistent case format, aiding in uniformity and reducing duplication.

5. Data Validation and Error Checking:
   - Conducted thorough checks for duplicates, missing values, and outliers to ensure data integrity. Corrections were made where necessary to tidy the dataset, making it reliable for analysis.

6. Documentation and Annotation:
   - Each step of the data cleaning process was meticulously documented to provide clarity and aid in reproducibility. Annotations and descriptions were added to explain the logic behind each decision and method used.

 Tools Used
- Microsoft Excel: Leveraged for its robust data manipulation capabilities, including text-to-column, pivot tables, and various text and lookup functions.


 Usage
The cleaned dataset can be utilized by analysts and data scientists within the consumer goods industry to conduct market analysis, inventory management, and strategic planning. The methodologies applied here can also serve as a guideline for similar data cleaning projects, promoting best practices in data management.

 Contribution
Contributions to this project are welcome, especially in the form of improved data cleaning scripts, additional documentation, or novel uses of the cleaned data. Suggestions for further enhancements or corrections are appreciated to refine the dataset and its utility further.

This project not only sets a foundation for rigorous digital data management in Bangladesh but also aims to enhance the analytical capabilities within the local market, fostering informed business decisions based on high-quality data.
