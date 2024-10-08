<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Anonymous E-Commerce Platform Survey</title>
    <!-- Add some basic styling to make the form look better -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            max-width: 600px;
            margin: auto;
        }
        label {
            font-weight: bold;
        }
        input, textarea, select {
            width: 100%;
            padding: 8px;
            margin: 5px 0 15px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1> Anonymous E-Commerce Platform Survey</h1>
    <p>We appreciate your feedback! Please take a few minutes to complete this survey and help us improve our e-commerce platform.</p>
    <form action="process_survey.php" method="post">
      
      

        <!-- Overall Satisfaction -->
        <label for="satisfaction">Overall Satisfaction with the Platform:</label>
        <select id="satisfaction" name="satisfaction" required>
            <option value="">Select an option</option>
            <option value="1">1 - Very Dissatisfied</option>
            <option value="2">2 - Dissatisfied</option>
            <option value="3">3 - Neutral</option>
            <option value="4">4 - Satisfied</option>
            <option value="5">5 - Very Satisfied</option>
        </select>

        <!-- Website Usability -->
        <label for="usability">How easy was it to navigate the website?</label>
        <select id="usability" name="usability" required>
            <option value="">Select an option</option>
            <option value="1">1 - Very Difficult</option>
            <option value="2">2 - Difficult</option>
            <option value="3">3 - Neutral</option>
            <option value="4">4 - Easy</option>
            <option value="5">5 - Very Easy</option>
        </select>

        <!-- Product Quality -->
        <label for="product_quality">How satisfied are you with the quality of the products?</label>
        <select id="product_quality" name="product_quality" required>
            <option value="">Select an option</option>
            <option value="1">1 - Very Dissatisfied</option>
            <option value="2">2 - Dissatisfied</option>
            <option value="3">3 - Neutral</option>
            <option value="4">4 - Satisfied</option>
            <option value="5">5 - Very Satisfied</option>
        </select>

        <!-- Checkout Experience -->
        <label for="checkout_experience">How would you rate your checkout experience?</label>
        <select id="checkout_experience" name="checkout_experience" required>
            <option value="">Select an option</option>
            <option value="1">1 - Very Poor</option>
            <option value="2">2 - Poor</option>
            <option value="3">3 - Neutral</option>
            <option value="4">4 - Good</option>
            <option value="5">5 - Excellent</option>
        </select>

        <!-- Customer Support -->
        <label for="customer_support">How satisfied are you with our customer support?</label>
        <select id="customer_support" name="customer_support" required>
            <option value="">Select an option</option>
            <option value="1">1 - Very Dissatisfied</option>
            <option value="2">2 - Dissatisfied</option>
            <option value="3">3 - Neutral</option>
            <option value="4">4 - Satisfied</option>
            <option value="5">5 - Very Satisfied</option>
        </select>

        <!-- Delivery Experience -->
        <label for="delivery_experience">How would you rate your delivery experience?</label>
        <select id="delivery_experience" name="delivery_experience" required>
            <option value="">Select an option</option>
            <option value="1">1 - Very Poor</option>
            <option value="2">2 - Poor</option>
            <option value="3">3 - Neutral</option>
            <option value="4">4 - Good</option>
            <option value="5">5 - Excellent</option>
        </select>

        <!-- Future Purchase -->
        <label>Would you purchase from us again?</label><br>
        <input type="radio" id="yes" name="future_purchase" value="yes">
        <label for="yes">Yes</label><br>
        <input type="radio" id="no" name="future_purchase" value="no">
        <label for="no">No</label><br><br>

        <!-- Recommendations -->
        <label for="recommendation">Would you recommend us to others?</label>
        <select id="recommendation" name="recommendation" required>
            <option value="">Select an option</option>
            <option value="1">1 - Definitely Not</option>
            <option value="2">2 - Probably Not</option>
            <option value="3">3 - Maybe</option>
            <option value="4">4 - Probably Yes</option>
            <option value="5">5 - Definitely Yes</option>
        </select>

        <!-- Additional Comments -->
        <label for="comments">Additional Comments or Suggestions:</label><br>
        <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br>

        <!-- Submit Button -->
        <input type="submit" value="Submit">
    </form>
</body>
</html>
