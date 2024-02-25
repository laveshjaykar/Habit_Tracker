# Habit Tracker 

This Python script leverages the Pixela API, a "habit tracker" service that allows you to create and manage your habit tracking graphically in a pixel art style. Specifically, this script is designed to track the number of pages you read each day.

How It Works

User Creation: First, the script sets up a new Pixela user account using the provided username and token. Note that this part of the code is commented out because user creation is a one-time setup.
Graph Creation: Next, it creates a graph named "Pages Read" where each pixel represents the number of pages read on a particular day. The graph's ID is set to graph2, and the color scheme for the graph is shibafu (a shade of green).
Daily Pixel Update: Finally, the script prompts you to enter the number of pages you read today. It then updates the "Pages Read" graph with a new pixel representing today's reading.
