# write the answer
import numpy as np

# Exam scores for a group of students
np.random.seed(42)  # Set seed for reproducibility

# Generating random exam scores between 0 and 100 for 50 students
exam_scores = np.random.randint(0, 101, 50)
# Mean

mean = np.mean(exam_scores)

# Median
median = np.median(exam_scores)

# Standard Deviation
std_dev = np.std(exam_scores)

# Range
range_of_scores = max(exam_scores)-min(exam_scores)
# Mode
mode = np.argmax(np.bincount(exam_scores))

# Display the dataset
print("Exam Scores:")
print(exam_scores)
print("Mean:", mean)
print("Median:", median)
print("Standard Deviation:", std_dev)
print("Range:", range_of_scores)
print("Mode:", mode)

