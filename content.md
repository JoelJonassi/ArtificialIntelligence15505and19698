# Introduction

This practical work intends to increase the knowledge acquired during Artificial Intelligence classes through the development of an intelligent agent.
In the current scenario of energy crisis, it is intended to reschedule the schedules of classes of the undergraduate courses of the school of technology in order to reduce travel to campus and to lower the need for air conditioning.

Some constraints:

- All lessons, with a duration of 2 hours, take place on weekdays.
- All classes have 10 lessons per week, of which 1 or 2 lessons are online.
- A class should not have more than 3 lessons per day. Online lessons cannot be booked immediately or immediately after a face-to-face lesson.
- Only up to 2 lessons can take place in the morning and up to 2 lessons in the afternoon.
- Every class has 2 to 4 lessons in a specific classroom.
- Can’t assign a classroom that it is already occupied to another class;
- Assign a classroom to a class according to a total of students of that class;
- Teachers can choose the schedule that they like;
- All lessons must start at least at 9am and end at most by 6pm.
- Teachers can't have more than xx hours per day.

According to the constraints described above we will formulate and implement an agent that finds the best solution for class schedules, minimizing the number of days each class must travel to campus and the number of classrooms used. Solutions that have schedules with fewer holes should be valued.
We will end with a small conclusion, where we will summarize the development of the project, alluding to the difficulties encountered.

# Goal formulation

- Goal: Assign schedule to lessons;

- Actions:
    - (A) assign schedule to a classroom;
    - (U) unassign schedule to a classroom;
    - (MD) move to another day;
    - (MH) move to another hour.

- Limitations:

  - There can not be two lessons in the same classroom at the same time;
  - There can be at most 3 lessons per day;
  - There must be 2 to 4 lessons in a specific classroom;
  - Only up to 2 lessons can take place in the morning and up to 2 lessons in the afternoon;
  - There must be 1 or 2 lessons online.
  - Online lessons cannot be booked immediately or immediately after a face-to-face lesson.

- Problem formulation:

  - State space: Occupied or Free.

- Initial State:
    - All schedules  are free.

- Actions: 
    - (A) assign schedule to a classroom;
    - (U) unassign schedule to a classroom;
    - (MD) move to another day;
    - (MH) move to another hour.

- Transition model
    - A schedule can be occupied (A) if it is free;
    - MD and MH actions changes the position of the agent;
    - 

- Goal states:
  - Every lessons has a day and the start hour.

- Action cost
    - Each step costs 1, and the solution cost is the number of steps to solve the problem.

# Agent structure and function

## Attributes of the agent(PEAS):

- Performance:
  Reduce cost of travels, reduce the number of classrooms used,

- Environment:
  School, classrooms, students, teachers, staff.

- Actuator:
  Display of schedules
  Air conditioner
  Lessons

- Sensors:
  ...

## Characteristics of the task environment:

This environment is fully observable ...

Deterministic...

Sequential ...

Static...

Discrete...

## Search problem

### Pseudo-code

## Heuristic

# Agent running

<<Provide solutions for one or, if possible, several initial states. Perform a critical analysis of the results and identify some future improvements to the agent. Please include a link to the code repository.>>

# Conclusion

<< Insert here a conclusion about the outcomes accomplished, the development process and the tools used. The structure of the report should be adapted according to each project characteristics. Don’t forget to remove these comments (help text)!>>
