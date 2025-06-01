 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form - Shiv Yadav</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 id="title">Shiv Yadav - Survey Form</h1>
    <p id="description">Help us improve our YouTube content by filling out this short survey.</p>
    
    <form id="survey-form">
        <label id="name-label" for="name">Your Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>

        <label id="email-label" for="email">Your Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>

        <label id="number-label" for="number">Your Age (Optional):</label>
        <input type="number" id="number" name="number" min="10" max="100" placeholder="Enter your age">

        <label for="dropdown">How often do you watch our videos?</label>
        <select id="dropdown" name="dropdown">
            <option value="daily">Daily</option>
            <option value="weekly">Weekly</option>
            <option value="monthly">Monthly</option>
            <option value="rarely">Rarely</option>
        </select>

        <label>Which type of content do you like the most?</label>
        <input type="radio" name="content" value="tech"> Tech Videos
        <input type="radio" name="content" value="vlogs"> Vlogs
        <input type="radio" name="content" value="reviews"> Reviews

        <label>Which topics do you want to see more? (Select multiple)</label>
        <input type="checkbox" name="topics" value="programming"> Programming
        <input type="checkbox" name="topics" value="gadgets"> Gadgets
        <input type="checkbox" name="topics" value="lifestyle"> Lifestyle

        <label for="feedback">Any suggestions or feedback?</label>
        <textarea id="feedback" name="feedback" rows="4" placeholder="Write your feedback here..."></textarea>

        <button type="submit" id="submit">Submit</button>
    </form>
</body>
</html>
