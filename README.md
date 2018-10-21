# GitLog2Diary

## Description

A script to generate diary from git log, this is required by COMP9041 assignment 2 in 2018S2.

## Git Commit Message Format

**Important: to generate valid diary, git commit message must follow a special format**

**重要：为了生成有效日志，git commit 内容必须遵循特定格式**

```shell
git commit -m "01:30 your commit message"
```
- [01:30]: The hours and minutes used for this commit, a white space is followed. If omitted, this commit will be ignored when generating diary.

## Full Usage

```shell
./GitLog2Diary.pl ["Author"] [> diary.txt]
```

- [Author]: specify an author. If omitted, all author will be matched.
- [> diary.txt]: output as a text file. If omitted, just print out the diary.

## Output Example

```shell
/GitLog2Diary.pl
```

Start Time  |Stop Time   |Comments                                      
------------|------------|----------------------------------------------
21/10 20:32 |21/10 20:34 |add hello world
21/10 19:34 |21/10 20:46 |add some lines of code
21/10 20:53 |21/10 21:23 |almost finish
21/10 21:25 |21/10 21:26 |remove vstages