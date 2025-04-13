PyTest

PyTest is a very popular testing framework in Python that lets us write simple tests as functions.
It automatically discovers test files (for example files that start with test_)
It has powerful features like:
- Fixtures (for setup/teardown code)
- Parameterized tests (to test with multiple inputs)
- Plugins and integrations (for example with coverage tools)

A framework is a collection of tools, libraries, conventions that help us build and structure our software more efficiently.
A framework is some software that’s already been developed and is used to help us create our own application. So it’s basically resusable code that provides specific functionality that we can use in our programs. The point of a framework is to avoid reinventing the wheel.
Let’s say that we need to sort some names alphabetically. If we write the code for this ourselves it wouldn’t be efficient and waste of time. Because there is some code out there that we can use to do this. With frameworks we can focus on our program and not worry about low level stuff.
Frameworks are already tested and being used by many programmers. So it means frameworks are efficient. A good programmer knows about frameworks and use them.

Selenium is a tool for automating web browsers. It’s not specific to Python, it has bindings for Java, C#, Python etc. Use cases of Selenium:
- Test web applications by simulating user actions (clicks, typing, etc.)
- Web scraping (The automated process of extracting data from websites using software, often referred to as bots or crawlers. It involves requesting web pages, parsing their HTML content, and extracting the desired information, which can then be stored or used for various purposes.)

PyTest uses simple Python assert statements to perform testing, making it readable and maintainable. It's ideal for both unit and integration testing.

PyTest Tutorial (https://www.youtube.com/watch?v=cHYq1MRoyI0)

PyTest has a feature of automatically discovering tests. For example we name a file like “test_EMV” and PyTest will know that there is a test in this file. Or we can do it for functions. For example “test_function1”. PyTest automatically identifies which functions and methods are tests based on their names. PyTest also simplifies the test execution we just run the command “pytest”.


