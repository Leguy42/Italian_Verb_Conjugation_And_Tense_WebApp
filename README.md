# Italian_Verb_Conjugation_And_Tense_WebApp
A simple web app that generates exercises to study Italian verbs. You choose the verbs (-are, -ere, -ire) or use the default samples and verb tense. Then It generates a worksheet webpage for you to fill in. When you've completed the exercise, it checks and scores your work. It has an API sourcing a dictionary and allows you to track your progress.

Key Features:

Fillable Web Worksheet - Instead of PDF, you practice directly in the browser with interactive fill-in fields
Auto-Translation - Type either Italian or English and the app automatically populates the other field using the MyMemory translation API (free, no key needed)
Dictionary Integration - Uses online translation APIs so the app isn't bogged down with dictionary data. It fetches translations on-demand with a smart debounce delay
"Soluzioni" Answer Checking:

Shows correct answers in green ✓
Shows incorrect answers in red ✗ with the correct answer displayed
Displays a beautiful results modal with your percentage score
Breaks down "X correct out of Y total"

Progress Tracking (Optional):
Toggle "Track my progress over time" checkbox
Stores data in browser's localStorage
Displays stats: Total Attempts, Average Score, Best Score
Persists across sessions

How It Works:
Setup Phase: Add verbs (type Italian or English, the other auto-populates), select tense, choose whether to track progress
Practice Phase: Fill in all conjugations for each verb
Check Results: Click "Soluzioni" to see which answers are correct/incorrect and view your score
Review or Retry: Review mistakes or clear answers and try again

The app uses a simplified conjugation algorithm for common regular verbs, which works great for learning the patterns. For production use with irregular verbs, you could integrate a more comprehensive API like Verbix (though it requires authentication).
Open the HTML file in your browser and start practicing!
