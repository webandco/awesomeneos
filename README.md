# AwesomeNeos
AwesomeNeos is a collection Neos CMS package for pre production.

## Focus
In order to create awesome websites it's very important to have all the information you need. The most important one is to know your clients' content. The idea is to work in very flexible pre production circle iterations to collect your clients' content.

- Discussion
- Structure
- Content
- Documentation

This package is a collection of packages to help you achieve this goal right within Neos CMS. This quote is a nice summary of what the general focus of this project is.

> "Use Neos CMS for wireframes, then add content, then design; clients work with Neos from day one"

Watch the Neos Conference task about it to get more information: [Neos Conference: No more “Lorem Ipsum” - wireframing and content first with Neos CMS](https://www.neos.io/blog/neos-conference-2017.html)

## Packages

 - webandco/neos-bootstrap
 - webandco/neos-wireframe

### Install via composer
```composer require webandco/awesomeneos```

## How to use it
After installing the package you can use these content node types to structure the page:

 - Neos.NodeTypes:TwoColumn
 - Neos.NodeTypes:ThreeColumn
 - Neos.NodeTypes:FourColumn
 - Webandco.Bootstrap:OneColumn

Within each column you can create wireframe boxes that will be fully responsive in your grid configuration.
Each wirefame box is a content collection that can contain other content nodes. Depending on the editing mode you will see the abstract wireframe box or the content contained.

### Contribute
If you want to help to improve this project, or you have created a package that improves the pre production capabilities of Neos CMS, create a pull request.
