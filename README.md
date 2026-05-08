# ncu-hacks-1.0

My solutions for NCU Hacks 1.0, a competitive programming hackathon hosted on CodeChef and run at NIIT University across two rounds. Each file solves one CodeChef problem (problem code in the filename, e.g. `ONEVONE244`).

## Layout

```
round-1/   # round 1 solutions (Java)
round-2/   # round 2 solutions (Java, Python)
```

Each source file is a self-contained CodeChef submission — read input from stdin, write the answer to stdout.

## Running a Java solution

```bash
javac round-1/ONEVONE244.java
java -cp round-1 Codechef < input.txt
```

(All files declare `class Codechef` to match CodeChef's submission template.)

## Running a Python solution

```bash
python3 round-2/ONEVONE206.py < input.txt
```

## License

MIT
