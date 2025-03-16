This script automates the process of detecting and classifying new names in a database using machine learning. It is done by scanning a directory for the most recent and previous versions of a database stored in Excel files. The script extracts and cleans text-based features such as names, then compares new entries against old ones to identify differences.

Once trained, the models predict labels for new names, determining whether a name belongs to a known category, or if it should be flagged as an anomaly. The results, including new names, predictions, and anomaly scores, are saved in an Excel file, and trained models are stored for future use.

By analyzing the results of the models, you can choose the best model for your data.
