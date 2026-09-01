# CS50-Project
Final Project for CS50P course

<!--#To do:\
= decide the function of the project -- done!\
= code it\
= implement test functions\
= write README\
= shoot and upload a video\
= submit the form-->

Project idea:\
A python program that would go beyond a basic "split the bill equally" calculator by:
- Tracking which person consumed which items
- Handling shared items (e.g., fries shared by two people)
- Splitting GST/tax proportionally
- Calculating each person's final amount accurately

Project structure:\
bill_splitter\
│\
├── project.py          # Main program\
├── models.py           # Person, Item, Bill classes\
├── utils.py            # Helper functions\
├── test_project.py     # Unit tests\
├── requirements.txt\
├── sample_bill.json\
└── README.md 

Algorithms:
- Split shared items evenly
- Calculate subtotals
- Apply proportional GST
- Apply proportional service charge
- Apply proportional discount
- Handle rounding so the final totals exactly equal the original bill
- Testing

Tests:
- Shared item splitting
- GST calculation
- Discounts
- Invalid input
- Rounding edge cases
