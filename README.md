<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blue and White Button</title>
    <style>
        /* Basic styling for the body to provide a background */
        body {
            font-family: 'Inter', sans-serif; /* Using Inter as per guidelines */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Make body at least full viewport height */
            margin: 0;
            background-color: #f0f8ff; /* A very light blue/off-white for the background */
            /* Ensure the body is responsive */
            width: 100%;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }

        /* Styling for the button */
   button {
            padding: 15px 30px; /* Top/bottom padding, left/right padding */
            font-size: 1.2em;
            font-weight: bold;
            color: #ffffff; /* White text color */
            background-color: #007bff; /* A vibrant blue background color */
            border: none; /* No default border */
            border-radius: 8px; /* Slightly rounded corners */
            cursor: pointer; /* Change cursor to pointer on hover */
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease; /* Smooth transition for hover effects */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow for depth */
            /* Ensure the button is responsive */
            max-width: 90%; /* Limit button width on smaller screens */
            box-sizing: border-box; /* Include padding and border in the element's total width and height */
        }

        /* Hover effect for the button */
  button:hover {
            background-color: #0056b3; /* Darker blue on hover */
            transform: translateY(-2px); /* Slight lift effect */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3); /* Enhanced shadow on hover */
        }

        /* Active (click) effect for the button */
   button:active {
            background-color: #004085; /* Even darker blue when clicked */
            transform: translateY(0); /* Reset lift effect */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); /* Smaller shadow when clicked */
        }

        /* Styling for the anchor tag, to remove default underline and inherit button styles */
  a {
            text-decoration: none; /* Remove underline from the link */
        }

        /* Basic responsive adjustments */
  @media (max-width: 600px) {
            button {
                font-size: 1em; /* Smaller font on small screens */
                padding: 12px 25px; /* Adjust padding for smaller buttons */
            }
        }
    </style>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <a href="live messaging platform.html">
        <button>Let's Chat</button>
    </a>
</body>
</html>
