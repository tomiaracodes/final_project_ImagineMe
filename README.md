# final_project_ImagineMe
Software Carpentry Spring 2025 Project

Due to GPU restrictions, this diffusion model will not include large amount of training data and epochs. 
This model will use huggingface's Stable Diffusion as a base model, and finetuning for African book characters will be performed to provide better resolution of these characters than state-of-the-art tools.
The scope of the project has changed to zeroing in on African characters due to large scope of possible books and authors.

# General Diffusion Pipeline
A CSV file, created manually by author, will serve as the training data and includes Character Name, Book, Author, ISBN, Character Description, and Character ID.
Based on finetuning specified below, images generated should be more realistic than state-of-the-art tools provide.
It will be geared towards book characters specifically written by African authors. Reducing stereotypes or eurocentric representations of Africans.

# Training Details for Textual Inversion
Training on three different groups (men, women and groups of people) was performed using huggingface's Textual Inversion Colab notebook. 
Learning Rate: 5e-04
Max train steps: 2000
Save steps: 250
Batch size: 1

Embeddings were generated for each training group. 



