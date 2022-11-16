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

According to the constraints described above we will formulate and implement an agent that finds the best solution for class schedules, minimizing the number of days each class must travel to campus and the number of classrooms used. Solutions that have schedules with fewer holes should be valued.
We will end with a small conclusion, where we will summarize the development of the project, alluding to the difficulties encountered.

# Goal formulation

- Goal: Reduce travel to campus and to lower the need for air conditioning.

- Actions: Assign classroom to a class, assign class to teacher, assign schedule to class…

- Limitations: 
If there are two classes in which your classes must be in a specific room and the same room, one class can only have classes after the other has.

- Problem formulation:
    - State space:


# Agent structure and function

## Attributes of the agent(PEAS):

- Performance: 
    Reduce cost of travels

- Environment: 
    School, student, teachers

- Actuator: 
    Display of schedules
    Air conditioner

- Sensors:
    Camera
    

## Characteristics of the task environment:

This environment is fully observable...

Stochastic...

Deterministic...

Sequential...

Static...

Discrete...

## Search problem
## Heuristic

# Agent running

<<Provide solutions for one or, if possible, several initial states. Perform a critical analysis of the results and identify some future improvements to the agent. Please include a link to the code repository.>>

# Conclusion

<< Insert here a conclusion about the outcomes accomplished, the development process and the tools used. The structure of the report should be adapted according to each project characteristics. Don’t forget to remove these comments (help text)!>>