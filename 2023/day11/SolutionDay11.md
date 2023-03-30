# Day 11 Task: Advance Git & GitHub for DevOps Part-2

## Task-01

- Create a new branch and make some changes to it.
 
   ![1](https://user-images.githubusercontent.com/77112379/228907361-1e855fda-6613-4fa7-81f5-4cd825a5f502.jpg)

- Use git stash to save the changes without committing them.

   ![2](https://user-images.githubusercontent.com/77112379/228907915-dfa8b549-26cc-44cb-9e03-2d6aa1bf5dd7.jpg)

- Switch to a different branch, make some changes and commit them and Use git stash pop to bring the changes back.

   ![3](https://user-images.githubusercontent.com/77112379/228908070-644bd417-c19a-4593-967b-2d37fc58131f.jpg)

   ![4](https://user-images.githubusercontent.com/77112379/228908384-297e6b8d-a4f6-43c3-81d8-6abd17c837d0.jpg)

- Apply changes on top of the new commits.

   ![5](https://user-images.githubusercontent.com/77112379/228908512-45d9dfe8-80e3-490c-b179-e582a486e908.jpg)

# Task-02
- In version01.txt of development branch add below lines after “This is the bug fix in development branch” that you added in Day10 and reverted to this commit.

- Line2>> After bug fixing, this is the new feature with minor alteration”

  Commit this with message “ Added feature2.1 in development branch”
- Line3>> This is the advancement of previous feature

  Commit this with message “ Added feature2.2 in development branch”
- Line4>> Feature 2 is completed and ready for release

  Commit this with message “ Feature2 completed”
- All these commits messages should be reflected in Production branch too which will come out from Master branch (Hint: try rebase).

    ![6](https://user-images.githubusercontent.com/77112379/228909683-cb7b4fcc-f911-4172-92ef-f9975071be8c.jpg)

    ![7](https://user-images.githubusercontent.com/77112379/228909748-5249745a-93fa-4bfb-879f-0f7dedc7b494.jpg)

    ![8](https://user-images.githubusercontent.com/77112379/228909782-860a4528-fc3c-4263-b790-34dbd53daa08.jpg)

# Task-03

- In Production branch Cherry pick Commit “Added feature2.2 in development branch” and added below lines in it.

    ![9](https://user-images.githubusercontent.com/77112379/228910522-f8449da3-9507-479c-acf9-8828b1338e89.jpg)

- Line to be added after Line3>> This is the advancement of previous feature
- Line4>>Added few more changes to make it more optimized.

    ![10a](https://user-images.githubusercontent.com/77112379/228911084-968a808b-d872-4ec8-affa-0146ef91b458.jpg)

- Commit : Optimized the feature

    ![10b](https://user-images.githubusercontent.com/77112379/228911204-ad527aae-f644-4db8-8a49-e4186de01b16.jpg)
