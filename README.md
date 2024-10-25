# Simplate

[![Simplate][project-logo]][project-url]

Simplate is a simple template for your README.md files. I made it for my projects to simplify the process of writing
such files. Simplate uses only Markdown syntax with headers, simple numerated/bullet lists, table structures, code 
blocks, thick-lists and links. Enough to jump-start your project!

[Live demo](https://github.com/artemoons/simplate/blob/master/README.md) - [Report Bug](https://github.com/artemoons/simplate/issues/new?assignees=artemoons&labels=bug&projects=&template=bug-report.md&title=%5BBUG%5D) - [Request Feature](https://github.com/artemoons/simplate/issues/new?assignees=artemoons&labels=enhancement&projects=&template=feature_request.md&title=%5BFEATURE%5D)

## About

Simplate, as you can guess, is formed out of two words - "simple" and "template". And that is almost everything you need
to know about this project. If you copied this text, here are some topics that can help you to start with:
* write about the purpose of your project, 
* which problem does it solve,
* describe some background if it's needed and any other information you might think can be important,
* but don't overload this section with lots of text

## Getting Started
### Required dependencies

Any information, that can be useful when launching your project. In this case we can cope with any text editor as
* Sublime text
* but in case of Java, you can type its version like
* Java 17
* Maven
* etc.

### Setup

In order to run this project, first of all you have to set up all required parameters for the launch. In case of
README.md files you don't have to set up any, but if we have Java application, for example, you have to modify these
settings in application.yml file, located in `resources` folder:
1. `another.parameter.option = true`
2. `run.environment = production`
3. `retry.count = 10`
4. If it's necessary, you can even mention multi-line code block like this:
```json
{
    "startDate": "2024-08-01",
    "endDate": "2024-08-25",
    "stringList": [
        "first item", "second item" 
    ]
}
```

Also it's possible to use table structure which gives very readable way of enumerating parameters.
| Parameter        | Required? | Default value | Description                                |
|------------------|-----------|---------------|--------------------------------------------|
| parameter_1      |   true    | value-1       | Default value for required parameter       |
| parameter_2      |   false   | value-2       | Table structures are easy to understand    |
| parameter_3      |    yes    | value-3       | And give information in very compact style |
| parameter_4      |     no    | value-4       | Use them wisely :-)                        |

You can try Emoji for "Required" column as well, eg.: ✅, ✔, ❎, ❌.

Once everything's described, it's time to make first launch!

### Executing program

At this step you can use plain text description with `run commands` inside or list with bullets
* like this
* describing how to run your software

Sometimes it's more suitable to use
1. numerated
2. lists
3. with `step-by-step` commands

So it's up to you to decide which one is better. The main aim of this paragraph is to give user all information
that is required to run program. Use different text styles **to accent on important things** when _needed_.

Here you can mention attributes of successful launch, for example, "after successfull launch 'Application launched on
port 8080' will be written in console".

## Troubleshooting

If there are some known backlog issues, limitations that users may stumble upon, you can mention it here with quick
solutions how to avoid them or any other helpful information.

Remember, as anywhere in this document, you are free to use sub-headers like this

### Level 3
#### Level 4
##### Level 5
So don't forget to combine it with your content to achieve maximum readability and clearness of given material.

## To-Do List / Backlog

Here you can describe future plans for you project, some kind of roadmap in tick-list format.

- [ ] Add Russian translation
- [x] Fix spacing between headers
- [ ] Format headers

## Version History

A quick look on important milestones of your app. Format is pretty clean and simple. You can add dates if you wish. 

* 0.0.2 (25 OCT 2024)
    * Refactoring and code optimizations
* 0.0.1 (9 OCT 2024)
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Authors / Contributors

Artem Utkin  
[tema-utkin.ru](https://tema-utkin.ru)

## Acknowledgments

Inspiration for this README.md was taken from
* [DomPizzie](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [othneildrew](https://github.com/othneildrew/Best-README-Template)


[project-logo]: images/logo.svg
[project-url]: https://github.com/artemoons/simplate