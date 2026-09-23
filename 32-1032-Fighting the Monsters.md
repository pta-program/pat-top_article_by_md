# 1032 Fighting the Monsters

- **分值：** 35分

## 题目描述

![dgsj.JPG](images/004493ac-7061-48f0-a16f-7219a8bb3fc0.jpg)

Many computer games are designed to attract players to gain achievements and badges through a series of battles. They must defeat the monster to reach their goal.

Now given $$N$$ bases in a map, a player is supposed to conquer all the bases and gain the badges one by one through the paths in the map, while each path is guarded by a monster.  Each monster has its own power and carries its own weapon.  The amount of energy taken to defeat a monster is the same as that of the monster's power.  Each weapon also has a power level.  When a monster is defeated, its weapon will be seized by the player.

Your job is to find a way to help the player conquer all the bases with minimum lose of energy.  If such a solution is not unique, you must find the one to seize maximum amount of weapon powers, which is guaranteed to be unique.

## Input Specification

Each input file contains one test case. For each case, the first line gives two positive integers $$N$$ and $$M$$ (both no more than $$10^4$$), being the total numbers of bases and monsters, respectively. Then $$M$$ lines follow, where the $$i$$-th line ($$i=1, \cdots , M$$) describes the $$i$$-th monster's information in the following format:

```
B1 B2 Power Weapon
```
where `B1` and `B2` are the indices (from 0 to $$N-1$$) of the two bases; `Power` and `Weapon` are both positive integers no more than $$10^4$$, corresponding to the power levels of the monster and its weapen.  It is guaranteed that at most one path (and hence one monster) is connecting each pair of different bases.

## Output Specification

Print in the first line the minimum lose of energy in order to conquer all the bases, and the maximum amount of weapon powers one can seize in a solution.  Then in the next line, print all the monsters to be defeated in ascending order of their indices.  All the numbers in a line must be separated by one space, and there must be no extra space at the beginning or the end of the line.

## Sample Input
```
6 9
4 3 32 3
1 5 43 5
1 0 32 3
0 2 28 8
4 2 19 1
2 3 28 10
0 4 28 2
1 2 28 3
3 1 19 1
```

## Sample Output
```
137 25
2 4 5 6 9
```
