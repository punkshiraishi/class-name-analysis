# Count Tailwind Classes
Count Tailwind counts Tailwind CSS classes used in the repository you specify.

# Usage
```bash
git clone git@github.com:punkshiraishi/count-tailwind-classes.git
cd count-tailwind-classes
TARGET=../sample-project ./main > result.txt
```

# Result
```result.txt
flex 1020
w-full 431
flex-row 409
items-center 408
font-bold 232
flex-col 231
justify-center 174
h-full 165
text-center 156
justify-between 150
flex-shrink-0 127
space-x-3 126
static 88
w-32 79
...
```

# Options
- `TARGET` - The directory of the source code you want to analyze. This is a required.
- `PREFIX` - Specify this if you are using the tailwindcss prefix. This is an optional.