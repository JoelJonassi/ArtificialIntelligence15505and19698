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

Variables: each time slot, that time slot can be assign with teachers, curricular unit and classroom.

The domain of each variable: 

  time slot ={09h00-10h00, 10h00-11h00, 11h00-12h00, 12h00-13h00,13h00-14h00, 14h00-15h00, 15h00-16h00, 16h00-17h00, 17h00-18h00, 18h00-19h00, 19h00-20h00, 20h00-21h00, 21h00-22h00, 22h00-23h00}

  days = {monday, tuesday, wednesday, thursday, friday}

  teachers = {t1, t2, t3, t4, t5, t6, t7, t8}

  classrooms = {c1, c2, c3, c4, c5}

  curricular units = {cu1, cu2, cu3, cu4}

- Goal: Assign schedule to lessons;


- Constraints:

  - There can not be two lessons in the same classroom at the same time;
  - There can be at most 3 lessons per day;
  - There must be 2 to 4 lessons in a specific classroom;
  - Only up to 2 lessons can take place in the morning and up to 2 lessons in the afternoon;
  - There must be 1 or 2 lessons online.
  - Online lessons cannot be booked immediately or immediately after a face-to-face lesson.
  - Teacher can be assigned one classroom at a time.



# Agent structure and function




## Attributes of the agent(PEAS):



## Characteristics of the task environment:

This environment is fully observable - if an agent’s sensors give it access to the complete state of the environment at each
point in time. The agent need not maintain any internal state to keep track of the world

Deterministic - If the next state of the environment is completely determined by the current state and the
action executed by the agent(s)

Sequential - the current decision could affect all future decisions.

Multi-Agent ...

Static - the environment does not change while an agent is deliberating

Discrete - It applies to the state of the environment, to the way time is handled, and to the percepts and actions of
the agent



## Constraint Satisfaction Problem - CSP

### Pseudo-code

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

## Heuristic

# Agent running

<<Provide solutions for one or, if possible, several initial states. Perform a critical analysis of the results and identify some future improvements to the agent. Please include a link to the code repository.>>

link Repository: 

# Conclusion

<< Insert here a conclusion about the outcomes accomplished, the development process and the tools used. The structure of the report should be adapted according to each project characteristics. Don’t forget to remove these comments (help text)!>>

