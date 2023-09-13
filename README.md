# SignatureAnalysis

## Description

This repository contains an application that implements the WeirdTextFormat-8 protocol. The protocol involves encoding and decoding strings into lists of integer values and vice versa. The encoding and decoding functions are provided in a library-like structure for easy integration into other projects.

## Usage

To use this application, you can follow these steps:

1. Clone this repository to your local machine.

2. Navigate to the project directory.

3. Install any necessary dependencies (if applicable).

4. Import the `encode` and `decode` functions into your own project or test harness.

Ensure that you have a valid input string for encoding and that the decoded output matches the original string.

## Examples

Here are some examples of input strings and their corresponding encoded values:

- Input String: "tacocat"
  Encoded: [267487694, 125043731]

- Input String: "never odd or even"
  Encoded: [267657050, 233917524, 234374596, 250875466, 17830160]

- Input String: "lager, sir, is regal"
  Encoded: [267394382, 167322264, 66212897, 200937635, 267422503]

- Input String: "go hang a salami, I'm a lasagna hog"
  Encoded: [200319795, 133178981, 234094669, 267441422, 78666124, 99619077, 267653454, 133178165, 124794470]

- Input String: "egad, a base tone denotes a bad age"
  Encoded: [267389735, 82841860, 267651166, 250793668, 233835785, 267665210, 99680277, 133170194, 124782119]

## Testing

We have included unit tests to ensure the correctness of the encoding and decoding functions. You can run these tests to verify that the code functions as expected. Refer to the test files in the repository for more details on how to run the tests.

## Contributing

If you would like to contribute to this project, please fork the repository, make your changes, and submit a pull request. We welcome contributions, bug reports, and feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
