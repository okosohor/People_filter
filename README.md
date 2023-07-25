# React People Table (Advanced) - Filterging and Sorting

> Here is [the working example](https://mate-academy.github.io/react_people-table-advanced/)

> Sorting and filtering tests are not implemented yet

Using code from the [React People Table](https://github.com/mate-academy/react_people-table-basics#react-people-table)
implement the ability to filter and sort people in the table.

1. All the filters and sort params should be saved as URL Search Params, so you could share the link to show exactly what you see.
1. Keep search params when navigating within the `People` page (when selecting a person or clicking the `People` link).
1. The sidebar with the filters should appear only when people are loaded.
1. `NameFilter` should update the `query` search param with the text from the input.
    - show only people with the `name`, `motherName` or `fatherName` that match the query case insensitive;
    - if the input is empty there should not be `query` in the search params.
1. `CenturyFilter` should allow to choose several centuries or all of them.
    - add `centuries` search params using `append` method  `getAll` method;
1. Implement sorting by `name`, `sex`, `born` and `died` by clicking on arrows in a `th`;
    - the first click on a column sorts people by the selected field ascending (`a -> z` or `0 -> 9`);
    - the second click (when people are already sorted ascending by this field) reverses the order of sorting;
    - the third click (when people are already sorted in reversed order by this field) disables sorting;
    - use `sort` search param to save sort field;
    - add `order=desc` (short for `descending`) if sorted in reversed order;
    - if sorting is disabled there should not be `sort` and `order` search params;

## Instructions

- Implement a solution following the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline).
- Use the [React TypeScript cheat sheet](https://mate-academy.github.io/fe-program/js/extra/react-typescript).
- Open one more terminal and run tests with `npm test` to ensure your solution is correct.
- Replace `<your_account>` with your Github username in the [DEMO LINK](https://<your_account>.github.io/react_people-table-advanced/) and add it to the PR description.



# [People_filter](https://okosohor.github.io/People_filter/)
This repository contains the source code and assets for the **People_filter** project.

You may try it on this page: [CLICK ME](https://okosohor.github.io/People_filter/)

## Description
The People_filter project is a web application that implements various filtering of data taken from the API. It is built using ***React***, ***JavaScript***, ***TypeScript***, ***HTML***, and ***MUI***.

## Features
- Filtering by different criteria.
- Ability to select a specific user (interaction with URL)
- Demonstration of React Router capabilities
- User search


## Acknowledgements
- React
- JavaScript
- TypeScript
- HTML
- MUI
- GitHub Pages for hosting the live demo

## Contributing
If you would like to contribute to this project, you can follow these steps:

1. Fork the repository.
2. Clone the forked repository: `git clone https://github.com/<your-username>/<project_name>.git`.
3. Navigate to the project directory: `cd People_filter`.
2. Create a new branch: `git switch -c feature/your-feature`.
3. Install packages: `npm i`.
4. Start the project: `npm start`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push the branch to your forked repository: `git push origin feature/your-feature`.
5. Open a pull request in this repository.

