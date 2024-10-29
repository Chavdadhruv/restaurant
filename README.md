<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Recommendation System</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
        }
        .container {
            margin-top: 50px;
        }
        h1 {
            color: #ff6347;
        }
        .card {
            border: none;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .icon {
            color: #ff6347;
        }
    </style>
</head>
<body>

<div class="container">
    <h1 class="text-center"><i class="fas fa-utensils icon"></i> Restaurant Recommendation System</h1>
    <p class="text-center lead">Built with <strong>Flask</strong>, this system provides personalized restaurant recommendations based on user preferences.</p>

    <div class="card mt-4">
        <div class="card-body">
            <h3 class="card-title text-primary">Overview</h3>
            <p>This <strong>Restaurant Recommendation System</strong> offers users tailored suggestions for restaurants based on their budget, preferred cuisine, location, and group size. By using <strong>cosine similarity</strong>, it matches users with restaurants that best align with their preferences. The system leverages a <strong>CSV dataset</strong> of restaurant information and employs <strong>CountVectorizer</strong> to analyze important features.</p>
        </div>
    </div>

    <div class="card mt-4">
        <div class="card-body">
            <h3 class="card-title text-primary"><i class="fas fa-star icon"></i> Key Features</h3>
            <ul class="list-unstyled ml-3">
                <li><strong>1. Search and Filter:</strong> Users can input preferences like number of people, budget range, cuisine, and location to receive tailored recommendations.</li>
                <li><strong>2. Recommendation Algorithm:</strong> Using cosine similarity on restaurant features, the system ranks and displays the best matches for the user’s needs.</li>
                <li><strong>3. Web Interface:</strong> A responsive, clean UI powered by HTML and Bootstrap ensures a seamless user experience with a simple search form.</li>
                <li><strong>4. Real-time Filtering:</strong> Users can refine their search and instantly get updated recommendations, including favorite restaurant selections.</li>
            </ul>
        </div>
    </div>

    <div class="card mt-4">
        <div class="card-body">
            <h3 class="card-title text-primary"><i class="fas fa-cogs icon"></i> Tech Stack</h3>
            <ul class="list-group list-group-flush">
                <li class="list-group-item"><strong>Backend:</strong> Flask framework</li>
                <li class="list-group-item"><strong>Data Processing:</strong> pandas, scikit-learn (CountVectorizer, cosine similarity)</li>
                <li class="list-group-item"><strong>Frontend:</strong> HTML, Bootstrap, and Font Awesome for styling and interactivity</li>
            </ul>
        </div>
    </div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
