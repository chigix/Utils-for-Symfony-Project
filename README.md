Utils-for-Symfony-Project
=========================

Some utils for a symfony bundle as a project development and IDE integration suggestion.

# Symfony bundle development styleguide

## Directory structure

	ExampleBundle/
		|-Controller
		|-DependencyInjection
		|-Entity
		|-Resources
		|-Tests
		|-app

Except the `app/` directory, others follows the conventions from Symfony itself, and most of them could be auto-created when generating the target bundle.

The `app/` directory was provided from this project.

The whole bundle project structure could be imported into Netbeans and recognized by the Netbeans Symfony2 plugin supporting.

And then, the developer could modified the chigi_routing.yml containing only routes for the current bundle.