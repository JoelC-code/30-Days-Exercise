# 30 Days Exercise2

Class:
1. Account (int IDaccount, String Username, String Password)
- Users (int age, String gender, double height, double weight, boolean haveOccupation, int dayAvailableExercise)
- Admin (Exercise Manager)
2. WorkoutPlan (Exercise (Queue [so it started one by one and not randomized], int selectedDays, boolean isDone)
- addWorkout (enqueue)
- removeWorkout (dequeue)
- checkWorkout (peek)
3. Calender (int day, int week, month) [pakai library java.util.Calendar and java.text.import java.text.DateFormatSymbols]
4. Exercise (int ID, String nameExercise, int calorieTotal, int repExercise, int setExercise, String<> areaBadan)
- Light exercise 
- Heavy exercise 
5. (Interface) Syarat Gerakan 
- Int CalorieCalculator()
