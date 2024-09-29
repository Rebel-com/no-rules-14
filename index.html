import React, { useState } from 'react';
import { Button } from '@/components/ui/button';
import { Input } from '@/components/ui/input';
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from '@/components/ui/select';
import { Textarea } from '@/components/ui/textarea';
import { Slider } from '@/components/ui/slider';

const SurveyForm = () => {
  const [answers, setAnswers] = useState({
    name: '',
    mostCompellingSection: '',
    perspectiveBalance: '',
    photoQuality: '',
    newInsight: '',
    captureOfJamesSmall: '',
    emotionalImpact: '',
    writingQuality: '',
    bookFormatSatisfaction: '',
    overallRating: 5,
    recommendationLikelihood: '',
    additionalComments: ''
  });

  const [submitted, setSubmitted] = useState(false);

  const handleChange = (question, value) => {
    setAnswers(prev => ({ ...prev, [question]: value }));
  };

  const handleSubmit = (e) => {
    e.preventDefault();
    setSubmitted(true);
  };

  const questions = [
    {
      id: 'mostCompellingSection',
      question: "2. Which section of the book did you find most compelling?",
      options: ['The Son', 'The Brother', 'The Father', 'The Man', 'The Player', 'The Coach', 'The Hero', 'The Legend', 'The Last Word']
    },
    {
      id: 'perspectiveBalance',
      question: "3. How well do you think the book balances different perspectives on James Small's life?",
      options: ['Excellent balance', 'Very good balance', 'Good balance', 'Fair balance', 'Poor balance']
    },
    {
      id: 'photoQuality',
      question: "4. How would you rate the quality and selection of photos in the book?",
      options: ['Excellent', 'Very good', 'Good', 'Fair', 'Poor']
    },
    {
      id: 'newInsight',
      question: "5. How much new insight did you gain into James Small's life and career?",
      options: ['A great deal', 'Quite a bit', 'A moderate amount', 'A little', 'None at all']
    },
    {
      id: 'captureOfJamesSmall',
      question: "6. How well do you think the book captures James Small as both a player and a person?",
      options: ['Extremely well', 'Very well', 'Well', 'Somewhat well', 'Not well at all']
    },
    {
      id: 'emotionalImpact',
      question: "7. Which aspect of James Small's story had the most emotional impact on you?",
      options: ['His family relationships', 'His rugby career', 'His personal struggles', 'His coaching career', 'His lasting legacy']
    },
    {
      id: 'writingQuality',
      question: "8. How would you rate the quality of writing by Gavin Rich and Simon Borchardt?",
      options: ['Excellent', 'Very good', 'Good', 'Fair', 'Poor']
    },
    {
      id: 'bookFormatSatisfaction',
      question: "9. How satisfied are you with the hardcover coffee-table book format?",
      options: ['Extremely satisfied', 'Very satisfied', 'Satisfied', 'Somewhat dissatisfied', 'Very dissatisfied']
    },
    {
      id: 'overallRating',
      question: "10. Overall, how would you rate \"No Rules: The James Small Story\"? (1-10)",
      type: 'slider'
    },
    {
      id: 'recommendationLikelihood',
      question: "11. How likely are you to recommend this book to other rugby fans or those interested in South African sports history?",
      options: ['Extremely likely', 'Very likely', 'Somewhat likely', 'Not very likely', 'Not at all likely']
    },
  ];

  const surveyResults = `1. What is your name: ${answers.name}\n\n` + questions.map(q => 
    `${q.question}\nAnswer: ${q.id === 'overallRating' ? `${answers[q.id]}/10` : answers[q.id]}`
  ).join('\n\n') + `\n\n12. Additional comments or feedback about the book:\n${answers.additionalComments}`;

  return (
    <div className="max-w-md mx-auto p-6 bg-white rounded-lg shadow-md">
      <h1 className="text-2xl font-bold mb-6 text-black">No Rules: The James Small Story - Reader Survey</h1>
      {!submitted ? (
        <form onSubmit={handleSubmit} className="space-y-6">
          <div>
            <label htmlFor="name" className="block mb-2 font-medium">
              1. What is your name:
            </label>
            <Input
              id="name"
              value={answers.name}
              onChange={(e) => handleChange('name', e.target.value)}
              required
            />
          </div>
          {questions.map((q) => (
            <div key={q.id}>
              <label htmlFor={q.id} className="block mb-2 font-medium">
                {q.question}
              </label>
              {q.type === 'slider' ? (
                <>
                  <Slider
                    id={q.id}
                    min={1}
                    max={10}
                    step={1}
                    value={[answers[q.id]]}
                    onValueChange={(value) => handleChange(q.id, value[0])}
                  />
                  <span className="block mt-1 text-sm">{answers[q.id]}/10</span>
                </>
              ) : (
                <Select onValueChange={(value) => handleChange(q.id, value)}>
                  <SelectTrigger>
                    <SelectValue placeholder="Select an option" />
                  </SelectTrigger>
                  <SelectContent>
                    {q.options.map((option) => (
                      <SelectItem key={option} value={option}>{option}</SelectItem>
                    ))}
                  </SelectContent>
                </Select>
              )}
            </div>
          ))}
          <div>
            <label htmlFor="additionalComments" className="block mb-2 font-medium">
              12. Do you have any additional comments or feedback about the book?
            </label>
            <Textarea
              id="additionalComments"
              value={answers.additionalComments}
              onChange={(e) => handleChange('additionalComments', e.target.value)}
              rows={3}
            />
          </div>
          <Button type="submit" className="w-full">Submit</Button>
        </form>
      ) : (
        <div className="space-y-4">
          <h2 className="text-xl font-semibold">Thank you for your feedback!</h2>
          <p>Please copy the text below and paste it into your WhatsApp message:</p>
          <pre className="bg-gray-100 p-3 rounded-md whitespace-pre-wrap">
            {surveyResults}
          </pre>
        </div>
      )}
    </div>
  );
};

export default SurveyForm;
