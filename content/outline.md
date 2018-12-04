## Outline
{:#outline}

We plan a half day for this tutorial as shown in [](#planning).
First, we will cover the basics of Comunica.
In the next session, the more advanced concepts will be handled.
Both sessions will start with short presentations,
and the end will be practical.

The first session will consist of an introductory presentation
in which the motivation and purpose of Comunica will be explained,
followed by an overview of its architecture.
Next, we will demonstrate the usage of Comunica
with several SPARQL queries in the [browser-based client](http://query.linkeddatafragments.org/){:.mandatory}.
After that, we will guide the audience through the installation
and usage of Comunica within a JavaScript application.

In the second session, we will focus on the configuration and extensibility of Comunica.
We will first give an overview of [Components.js](cite:cites componentsjs),
which is a dependency injection framework
that Comunica relies upon to handle the configuration of engines.
After that, we will guide the audience through plugging in a simple new querying algorithm
inside Comunica using the configuration system.

The tutorial will be guided by slides,
which will be shared online after the session.
For the hands-on coding sessions, we will provide
a git repository with separate branches for all sequantially completed tasks.
This will allow participants that are unable to complete a certain task,
to still begin with the next task by checking out a different branch.

<figure id="planning" markdown="1" class="table">

|                                  | Topic | Duration |
|----------------------------------|-------|----------|
| **Part 1: basic** (_1:30_)       | Introduction to Comunica | 0:30   |
|                                  | Browser usage examples  | 0:15   |
|                                  | Usage inside an application | 0:45   |
| **Part 2: advanced** (_1:30_)    | Configuration with Components.js | 0:30   |
|                                  | Adding a custom algorithm | 1:00   |

<figcaption markdown="block">
Planning of the Comunica tutorial
</figcaption>
</figure>
