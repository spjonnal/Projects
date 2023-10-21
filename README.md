# Projects
Machine Learning Projects
Description
# Goal of the Competition
The goal of this competition is to assess the quality of summaries written by students in grades 3-12. You'll build a model that evaluates how well a student represents the main idea and details of a source text, as well as the clarity, precision, and fluency of the language used in the summary. You'll have access to a collection of real student summaries to train your model.
# Dataset Description
The dataset comprises about 24,000 summaries written by students in grades 3-12 of passages on a variety of topics and genres. These summaries have been assigned scores for both content and wording. The goal of the competition is to predict content and wording scores for summaries on unseen topics.

# File and Field Information
summaries_train.csv - Summaries in the training set.
student_id - The ID of the student writer.
prompt_id - The ID of the prompt which links to the prompt file.
text - The full text of the student's summary.
content - The content score for the summary. The first target.
wording - The wording score for the summary. The second target.
summaries_test.csv - Summaries in the test set. Contains all fields above except content and wording.
prompts_train.csv - The four training set prompts. Each prompt comprises the complete summarization assignment given to students.
prompt_id - The ID of the prompt which links to the summaries file.
prompt_question - The specific question the students are asked to respond to.
prompt_title - A short-hand title for the prompt.
prompt_text - The full prompt text.
prompts_test.csv - The test set prompts. Contains the same fields as above. The prompts here are only an example. The full test set has a large number of prompts. The train / public test / private test splits do not share any prompts.
sample_submission.csv - A submission file in the correct format. See the Evaluation page for details.
