# Французька академія - Інтерактивне навчання

## 🇫🇷 French Learning App for Ukrainian Speakers

An interactive web application designed specifically for Ukrainian speakers to practice French verb conjugations and grammar at B2 level. The app provides a comprehensive learning experience with gamification elements and progress tracking.

## ✨ Features

### 📚 Exercise Categories
- **Conjugation** - Practice verb conjugations in different tenses
- **Negation** - Learn negative forms and structures  
- **Questions** - Master question formation and interrogative pronouns
- **Sentences** - Build complete sentences with word selection
- **Context** - Understand grammar in situational contexts
- **Speed** - Quick-fire exercises with time pressure

### 🎯 Difficulty Levels
- **Beginner** - Basic grammar concepts and simple structures
- **Intermediate** - More complex forms and varied vocabulary
- **Advanced** - Sophisticated grammar and academic language

### 🏆 Gamification
- **Progress Tracking** - Monitor your learning journey
- **Achievements** - Unlock badges for milestones
- **Streaks** - Build consecutive correct answer chains
- **Level System** - Advance through learning levels
- **Review System** - Practice previous mistakes

### 📊 Balanced Content
- **30 questions per category per difficulty level**
- **540 total questions** across all exercises
- **Consistent learning experience** with equal content distribution

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser
3. Start learning immediately!

```bash
# If using git
git clone [repository-url]
cd frenchlearningapp
# Open index.html in browser
```

## 📖 How to Use

### 1. Choose Your Exercise
- Click on any exercise tab (Conjugation, Negation, Questions, etc.)
- Select your difficulty level (Beginner, Intermediate, Advanced)

### 2. Complete Exercises
- **Conjugation/Negation/Questions**: Fill in the blanks with correct forms
- **Sentences**: Click words to build complete sentences
- **Context**: Choose appropriate words based on context
- **Speed**: Answer quickly within the time limit

### 3. Track Progress
- View your statistics in the top panel
- Check achievements and streaks
- Review mistakes in the dedicated review section

### 4. Review Mistakes
- Access the "🔄 Повторення помилок" tab
- Practice questions you previously answered incorrectly
- Improve accuracy over time

## 🎨 Technical Features

### Frontend
- **Pure HTML/CSS/JavaScript** - No frameworks required
- **Responsive Design** - Works on desktop and mobile
- **Modern UI** - Beautiful gradient design with smooth animations
- **Local Storage** - Progress saved automatically

### Data Structure
```javascript
exerciseData = {
  conjugation: {
    beginner: [30 questions],
    intermediate: [30 questions], 
    advanced: [30 questions]
  },
  // ... 5 more categories with same structure
}
```

### Key Functions
- `generateQuestions()` - Creates new exercise sets
- `checkAnswers()` - Validates user responses
- `updateGameState()` - Tracks progress and achievements
- `setupSpeedTimer()` - Manages timed exercises
- `generateReviewQuestions()` - Creates review sessions

## 📊 Content Statistics

| Category | Beginner | Intermediate | Advanced | Total |
|----------|----------|--------------|----------|-------|
| Conjugation | 30 | 30 | 30 | 90 |
| Negation | 30 | 30 | 30 | 90 |
| Questions | 30 | 30 | 30 | 90 |
| Sentences | 30 | 30 | 30 | 90 |
| Context | 30 | 30 | 30 | 90 |
| Speed | 30 | 30 | 30 | 90 |
| **Total** | **180** | **180** | **180** | **540** |

## 🎯 Learning Objectives

### B2 Level Competencies
- **Grammar Mastery** - Advanced verb conjugations and structures
- **Contextual Understanding** - Grammar in real-world situations
- **Speed and Accuracy** - Quick response with correct forms
- **Question Formation** - Complex interrogative structures
- **Sentence Construction** - Building coherent French sentences

### Target Skills
- ✅ Verb conjugation in present, past, and future tenses
- ✅ Negative forms and structures
- ✅ Question formation and interrogative pronouns
- ✅ Sentence building with proper word order
- ✅ Contextual grammar application
- ✅ Speed and fluency development

## 🔧 Customization

### Adding New Questions
To add new questions to any category:

```javascript
// In the exerciseData object
conjugation: {
  beginner: [
    // Add new questions here
    { question: "Je ___ (être) étudiant", answer: "suis" },
    // ... more questions
  ]
}
```

### Modifying Difficulty Levels
Each category supports three difficulty levels:
- `beginner` - Basic concepts
- `intermediate` - Moderate complexity  
- `advanced` - Advanced structures

## 🎮 Gamification System

### Achievements
- **Перша правильна відповідь** - First correct answer
- **Серія з 5 правильних** - 5 correct answers in a row
- **Серія з 10 правильних** - 10 correct answers in a row
- **10 вправ виконано** - Complete 10 exercises
- **Ідеальний результат** - Perfect score

### Progress Tracking
- Total exercises completed
- Total correct answers
- Current streak
- User level progression
- Achievement unlocks

## 🌟 User Experience

### Interface Features
- **Clean Design** - Modern gradient background
- **Intuitive Navigation** - Easy tab switching
- **Visual Feedback** - Color-coded correct/incorrect answers
- **Progress Indicators** - Real-time statistics display
- **Mobile Responsive** - Works on all screen sizes

### Learning Experience
- **Adaptive Difficulty** - Questions rotate to avoid repetition
- **Mistake Tracking** - Automatic review question generation
- **Time Pressure** - Speed exercises for fluency development
- **Contextual Learning** - Real-world grammar application

## 📱 Browser Compatibility

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers

## 🚀 Performance

- **Fast Loading** - Single HTML file with embedded resources
- **Offline Capable** - Works without internet connection
- **Lightweight** - No external dependencies
- **Responsive** - Optimized for all devices

## 🤝 Contributing

### Adding New Features
1. Fork the repository
2. Create a feature branch
3. Add your improvements
4. Test thoroughly
5. Submit a pull request

### Reporting Issues
- Describe the problem clearly
- Include browser and device information
- Provide steps to reproduce

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Designed for Ukrainian speakers learning French
- B2 level grammar and vocabulary focus
- Gamification inspired by modern language learning apps
- Responsive design principles for accessibility

---

**Start your French learning journey today! 🇫🇷🇺🇦**

Open `index.html` in your browser and begin practicing French grammar and verb conjugations with this comprehensive, gamified learning application.
