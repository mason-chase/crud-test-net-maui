# CRUD Code Test

Please read each note very carefully before start coding!

Create a simple CRUD application with that implements the below model:

```
Customer {
	Firstname
	Lastname
	DateOfBirth
	PhoneNumber
	Email
	BankAccountNumber
}
```

## Project Type

Choose one of the following project template:

1. [Microsoft .NET Maui](https://learn.microsoft.com/en-us/dotnet/maui/get-started/first-app?tabs=vswin&pivots=devices-android)
2. [Android Template](https://developer.android.com/studio/projects/create-project)
3. [iOS Template](https://developer.apple.com/documentation/xcode/creating-an-xcode-project-for-an-app)


## Practices and patterns (Must)

- [TDD](https://en.wikipedia.org/wiki/Test-driven_development)
- [DDD](https://en.wikipedia.org/wiki/Domain-driven_design)
- [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development): [Acceptance Test](https://en.wikipedia.org/wiki/Acceptance_testing)
- Clean Architecture
- Clean Code
- Clean git commits that shows your work progress.

### Validations (Must)

- During Create; validate the phone number to be a valid *mobile* number only (You can use [Google LibPhoneNumber](https://github.com/google/libphonenumber) to validate number at the backend).

- A Valid email and a valid bank account number must be checked before submitting the form.

- Customers must be unique in database: By `Firstname`, `Lastname` and `DateOfBirth`.

- Email must be unique in the database.

### Storage (Must)

- Use database of choice to store data on the mobile.

- Store the phone number in a database with minimized space storage (choose `varchar`/`string`, or `Uint64` whichever store less space).

### Submit your result

Please clone this repository in a new github repository in private mode and share with ID: `mason-chase` in private mode on github.com and then create a [PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) that only shows what you have changed in the project, it means you must make sure that my commits are not erased from the history.
