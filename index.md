<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DS Project: Customer Segmentation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
        }
    </style>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen p-4">
    <div class="bg-white rounded-xl shadow-2xl p-8 max-w-4xl w-full mx-auto">
        <header class="text-center mb-10">
            <h1 class="text-4xl font-bold text-gray-800 tracking-tight">Data Science Project: Customer Segmentation</h1>
            <p class="mt-2 text-lg text-gray-500">An analysis of customer data to identify distinct market segments.</p>
        </header>
        <section class="mb-8">
            <h2 class="text-2xl font-semibold text-gray-700 border-b-2 border-gray-200 pb-2 mb-4">Project Overview</h2>
            <p class="text-gray-600 leading-relaxed">
                This project focuses on segmenting customers based on their demographic and behavioral data from a mall dataset. The goal is to identify distinct groups of customers, which can help in developing targeted marketing strategies. The analysis is performed using Python libraries such as Pandas, scikit-learn, and Plotly.
            </p>
        </section>
        <section class="mb-8">
            <h2 class="text-2xl font-semibold text-gray-700 border-b-2 border-gray-200 pb-2 mb-4">Key Steps in the Analysis</h2>
            <div class="space-y-6">
                <!-- Step 1 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-inner">
                    <h3 class="text-xl font-semibold text-gray-800">1. Data Setup & Loading</h3>
                    <p class="mt-2 text-gray-600">
                        The project begins with setting up the Jupyter notebook environment, importing essential libraries like pandas for data manipulation, and loading the `Mall_Customers.csv` file into a DataFrame.
                    </p>
                </div>
                <!-- Step 2 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-inner">
                    <h3 class="text-xl font-semibold text-gray-800">2. Exploratory Data Analysis (EDA)</h3>
                    <p class="mt-2 text-gray-600">
                        Initial data exploration is performed to understand the dataset's structure, data types, and check for any missing or null values. This step ensures data quality before further analysis.
                    </p>
                </div>
                <!-- Step 3 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-inner">
                    <h3 class="text-xl font-semibold text-gray-800">3. Feature Engineering & Scaling</h3>
                    <p class="mt-2 text-gray-600">
                        Relevant features are prepared for the clustering algorithm. Data scaling is performed using `StandardScaler` to normalize the values and prevent features with larger scales from dominating the clustering process.
                    </p>
                </div>
                <!-- Step 4 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-inner">
                    <h3 class="text-xl font-semibold text-gray-800">4. K-Means Clustering</h3>
                    <p class="mt-2 text-gray-600">
                        The core of the analysis, K-Means clustering, is applied to the scaled data. This algorithm groups customers into distinct clusters based on their similarity, which represents different customer segments.
                    </p>
                </div>
                <!-- Step 5 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-inner">
                    <h3 class="text-xl font-semibold text-gray-800">5. Principal Component Analysis (PCA)</h3>
                    <p class="mt-2 text-gray-600">
                        To visualize the multi-dimensional data, PCA is used to reduce the data into three principal components. This allows for an effective representation of the clusters in a 3D space.
                    </p>
                </div>
                <!-- Step 6 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-inner">
                    <h3 class="text-xl font-semibold text-gray-800">6. 3D Data Visualization</h3>
                    <p class="mt-2 text-gray-600">
                        A 3D scatter plot is created using `Plotly Express`. The plot visualizes the customer clusters and allows for interactive exploration, providing insights into the characteristics of each segment.
                    </p>
                </div>
            </div>
        </section>
    </div>

</body>
</html>
