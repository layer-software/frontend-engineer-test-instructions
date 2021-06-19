## Welcome!

We are happy you have decided to take our coding challenge. We really hope you will have fun with it. Also, regardless of the evaluation outcome, we will give you feedback on your code.

At any time, please don't hesitate to ask any questions.

Happy coding!

## Task

Layer allows its users to share any part of an Excel spreadsheet. A user would upload their Excel spreadsheet on Layer app, and visually select areas they would like to share. 

To validate the concept, a basic prototype for the functionality has to be built. It will allow the user to choose one of already uploaded files, and select a region in it for sharing.

For the sake of simplicity:

- we are going to use a generic abstraction ("data table") of Excel files
- Data tables are provided small in the dataset, but you should assume they can potentially get quite big.
- cells can be selected only one by one
- no authentication is required
- designs need to be responsive only to the extent to fit various desktop screens. No need for mobile support.

Bonus points (surprise us!) for adding a feature of choice that you think will improve the UX of the application.

## Behaviours

- A data table can be selected for sharing from the list view
- Any number of cells can be marked for sharing
- Items can be removed from list of marked cells
- The list of marked cells cannot contain duplicates

## Dataset

A GraphQL server is provided [here](https://github.com/layer-software/frontend-engineer-test-server)

## UI

You'll find all screens in the [Figma document](https://www.figma.com/file/m7asKnKB3KhWksGqZ1CrT8/Frontend-Engineer-Challenge-Designs?node-id=0%3A1). You need to create a free Figma account to access the document in developer handover mode. You will be then able to select elements and view their properties, i.e., colours, margins, fonts etc.

<div class="display: flex">
    <img width="400" alt="List View" src="https://user-images.githubusercontent.com/33003/122649775-d7419680-d12f-11eb-89d4-28f710b68049.png">
    <img width="400" alt="Data Grid View" src="https://user-images.githubusercontent.com/33003/122649779-da3c8700-d12f-11eb-8ca3-b371bcc67ba7.png">
</div>

## Evaluation Criteria

Treat this task the same way as you would at work, aiming for deployment to production. 

We will pay attention to:

- **TypeScript** best practices
- Commit history: show us how you work
- Function: the program must be runnable and usable in the browser
- Structure: use of components & routing, management of data flow, use of GraphQL
- Completeness: did you complete the features?
- Correctness: does the functionality act in sensible, thought-out ways?
- Maintainability: is it written in a clean, maintainable way?
- How you have interpreted the UI designs and implemented them in a structured way
- Testing: is the system adequately tested?

## Deliverables

- Create a private repository on GitHub (they are free). When you finish the challenge, invite `bez4pieci` as a collaborator to the repository you created and send a notification e-mail to [careers@golayer.io](mailto:careers@golayer.io).
- Make sure you include all code in the repository.
- The task shouldn't take longer than ~3-4 hours of your time. Please be aware that we don't judge how fast you can code. If you feel you need more time to bring the solution to a state of your liking, please do so.
- If you choose to skip some parts or you believe your assumptions need explaining, please provide adequate details in the README.
