# Document Tracker Exercise

This exercise is split into 2 repositories;

- [Laravel API](#laravel-api)
- [Vue SPA](#vue-spa)

- You will need to clone each repository to complete the exercise.
- You will need to be able to run Laravel locally to complete the exercise. We use [Herd](https://herd.laravel.com/) - you are free to use any method you wish.
- Getting the application running locally is not part of the exercise. If you have any issues getting the application running locally, please contact us.
- The design of the application is not important. Please do not spend too much time on the design of the application. Please focus on the functionality of the application.
- After the completion of the exercise please keep your local environment running and ready to work on the application further during the review process.

## Laravel API

The Document Tracker API is available at [https://github.com/astalty/document-tracker-api](https://github.com/astalty/document-tracker-api).

Please view the `README.md` file for more information.

## Vue SPA

The Vue SPA (frontend) is available at [https://github.com/astalty/document-tracker-app](https://github.com/astalty/document-tracker-app).

Please view the `README.md` file for more information.

:::warning Important note about domains
As we use Laravel Sanctum for SPA authentication, the domain configuration is important. The API and SPA must share the same top level domain. You should serve the front end from `app.document-tracker.test` and the API from `api.app.document-tracker.test`.
:::

## Submitting your solution

Please upload your solution to your personal Github account and send us the link to the repositories.

## AI Usage

We strongly encourage the use of AI and during the review process you will be expected to outline the AI tools that you used including any example prompts or prompting strategies that you think are relevant to share.

## Exercise time

Please spend 1 to 1.5 hours on the exercise.

If you do not complete the exercise in this time, please submit what you have completed.

If you meet all the requirements within this time period, please feel free to add additional features or functionality to the application based on the [Business Problem](/requirements#business-problem).

## Assumptions

The [Business Problem](/requirements#business-problem) has been defined in a way that allows you to make assumptions about the problem.

## Details about the requirements

During this exercise, you are free to solve the problems in any way you see fit. You may use any packages or libraries you wish except;

- you can **not** use any packages or libraries that deal with file uploading and viewing such as [Spatie's Media Library](https://spatie.be/docs/laravel-medialibrary/v10/introduction)
- you should avoid using any backend packages where possible however you may install backend packages if you can justify their use and why you chose to use them
- you are free to use any frontend packages or libraries you wish

## Important notes

- Some boilerplate has been added to save some time and get started
- Tailwind CSS has been installed and configured for use - please use Tailwind if you are familiar with it
  - If you are not familiar with Tailwind, you may use vanilla CSS
- Whilst the application should look good, the focus of this exercise is about the functionality of the application. Please do not spend too much time on the design of the application
- Some backend code has been written however you should not assume this code is safe, functional or meets the requirements outlined in this challenge
- You may add new migrations if required, but you should not edit existing migrations
