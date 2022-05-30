0. Hello World
echo "Hello, World"

1. Confused smiley
echo "\"(Ôo)'"

2. Let's display a file
cat /etc/passwd

3. What about 2?
cat /etc/passwd /etc/hosts

4. Last lines of a file
tail /etc/passwd

5. I'd prefer the first ones actually
head /etc/passwd

6. Line #2
head -3 iacta | tail +3

7. It is a good file that cuts iron without making a noise

8. Save current state of directory
ls -la > ls_cwd_content

9. Duplicate last line
tail -n 1 iacta >> iacta

10. No more javascript
find . -type f -name "*.js" -delete

11. Don't just count your directories, make your directories count
find . -type d -not -name '.' | wc -l

12. What’s new
ls -t1 | head -n 10

13. Being unique is better than being perfect
sort | uniq -u

14. It must be in that file
grep -i "root" /etc/passwd

15. Count that word
grep -c -i "bin" /etc/passwd

16. What's next?
grep -i "root" -A 3 /etc/passwd

17. I hate bins
grep -i -v "bin" /etc/passwd

18. Letters only please
grep -i "^[a-z]" /etc/ssh/sshd_config

19. A to Z
tr "A" "Z" | tr "c" "e"

20. Without C, you would live in hiago
tr -d "cC"

21. esreveR
rev

22. DJ Cut Killer
cut -d ':' -f 1,6 /etc/passwd | sort

23. Empty casks make the most noise
find . -empty | rev | cut -d '/' -f 1 | rev

24. A gif is worth ten thousand words
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f

25. Acrostic
cut -c 1 | paste -s -d ''

26. The biggest fan
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev



