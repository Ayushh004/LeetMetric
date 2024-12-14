LeetMetric is a web-based application designed to help users track their problem-solving progress on LeetCode, a popular online platform for coding challenges. The tool provides an intuitive and interactive interface that visualizes user statistics and progress across different difficulty levels of problems (Easy, Medium, and Hard).

Key Features:
User-Friendly Input:

Users can enter their LeetCode username to fetch personalized stats.
The app validates the username using a regex pattern to ensure proper formatting.
Progress Visualization:

Displays progress using circular progress bars for Easy, Medium, and Hard problems.
Each circle dynamically updates based on the user's solved and total questions, using a conic-gradient design for a clean, modern look.
Detailed Statistics:

Shows overall performance stats, including metrics like total questions solved, and acceptance rate.
Stats are dynamically generated and displayed in visually appealing cards.
Responsive Design:

The app is designed to be responsive, ensuring a smooth experience across various devices.
The interface features a minimalistic design with a focus on readability and ease of navigation.
Backend Integration:

LeetMetric uses the LeetCode Stats API to fetch real-time user data.
It handles errors gracefully, displaying an appropriate message if the API fails to fetch data or the user is invalid.
Usage Workflow:
Enter your LeetCode username in the input field and click the "Search" button.
The app validates the input and fetches your stats from the API.
Progress for Easy, Medium, and Hard problems is displayed as percentage completion in circular progress bars.
Additional metrics, such as acceptance rate, are displayed in separate cards for quick insights.
Technologies Used:
HTML: For structuring the web page.
CSS: For styling and responsive design.
JavaScript: For fetching data from the API, validating user input, and updating the UI dynamically.
Purpose:
LeetMetric aims to help coders monitor their problem-solving progress on LeetCode, encouraging continuous improvement and providing motivation through clear visual feedback. It’s an excellent tool for aspiring programmers, competitive coders, and job seekers preparing for technical interviews.
