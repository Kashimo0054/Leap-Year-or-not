# Leap-Year-or-not
Check if the year entered by the user is a leap year or not.

Here is how the logic works

Is the year divisible by 4?
├── No → NOT a leap year
└── Yes → Is it divisible by 100?
          ├── No → IS a leap year
          └── Yes → Is it divisible by 400?
                    ├── No → NOT a leap year
                    └── Yes → IS a leap year
