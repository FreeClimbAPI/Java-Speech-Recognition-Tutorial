# Java - Speech Recognition Tutorial

This project serves as a guide to help you build an application with FreeClimb. Specifically, the project will:

- Make an outgoing Call
- Prompt the participant for a response
- Host a grammar file for speech recognition
- Use the users response

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://persephony-docs.readme.io/docs/getting-started-with-persephony).

## Setting up the Tutorial

1. Configure environment variables.

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                          |
   | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard                                                      |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard                                            |
   | TUTORIAL_APPLICATION_ID | Appliction IDs can be found under [Apps](https://www.persephony.com/dashboard/portal/applications)                                                                                   |
   | HOST                    | The url of where your app is being hosted (e.g. yourHostedApp.com)                                                                                                                   |
   | FREE_CLIMB_PHONE_NUMBER | The FreeClimb number that is being used to make a phone call. To learn more go [here](https://docs.persephony.com/docs/getting-started-with-persephony#section-2-get-a-phone-number) |

2) Provide a value for the variable `to` in speechRecognition.java. The `to` number is any phone number you wish to call. This number must be [verified](https://docs.persephony.com/docs/using-your-trial-account#section-verifying-outbound-numbers).

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```
