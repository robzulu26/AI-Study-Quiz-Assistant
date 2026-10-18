# AI-Powered Study & Quiz Assistant

## Project Overview

This is my CIT Capstone project. The goal of this project is to help students study for tests by using AI to create practice quizzes.

Students can upload their study notes as a PDF, and the AI will create multiple-choice questions based on the material. After answering the questions, students can see their scores, correct answers, and explanations.

## Features

1. **Upload Study Material:** Students can upload a PDF containing their study notes.

2. **Generate Quiz Questions:** The project uses Gemini AI to create multiple-choice questions based on the uploaded PDF.

3. **Take the Quiz:** Students can answer the questions without seeing the correct answers until they finish.

4. **Scores and Feedback:** After completing the quiz, students can see their score, which questions they got right or wrong, and explanations for the answers.

## Technologies Used

- Python
- Google Colab
- Gemini API
- PyPDF
- GitHub

## How to Run the Project

1. Open the `Capstone.ipynb` file in Google Colab.
2. Get a Gemini API key and add it to Colab Secrets with the name `GEMINI_API_KEY`.
3. Make sure notebook access is enabled for the API key.
4. Run the setup and Gemini API connection sections.
5. Run the Gemini API test to make sure the connection works.
6. Upload a PDF containing study notes.
7. Run the PDF extraction section to read the uploaded material.
8. Run the quiz generation section to create the questions.
9. Run the quiz section and answer each question.
10. Run the scores and feedback section to see the results.

## Testing

I tested the project using two different study guides, CompTIA A+ and Biology. Both were able to generate quiz questions, and I tested the scoring and feedback.

During testing, I ran into some problems with the PDF text formatting and the multiple-choice questions. I was able to fix these problems and get the quizzes working.

## Future Improvements

There are a few features I would like to add in the future.

- Allow students to type or paste their study notes instead of only uploading PDFs.
- Allow students to choose how many questions they want and whether they want multiple-choice or true/false questions.
- Create a better interface that makes the quizzes easier to use.

## Project Status

The main features of the project have been completed and tested using Google Colab. Students can upload a PDF, generate quiz questions, answer them, and receive their scores and feedback.

The project currently runs in Google Colab.
