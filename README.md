# General Gameplay Ideas

Hacknet RTS starts the player at the beginning of a journey down a dark road to the world of hacking for profit. Potential abilities:
- For-hire work to generate income
- Build bot nets to generate passive income
- Use funds to expand operation (cover cloud costs or hardware/software)
- Set up defenses to ensure your networks don't get hacked by others or the government

It seems only fitting that a hacking game allow for the ability to script virtually everything, creating a nearly automated method of generating income, from accepting jobs from the dark market (e.g. Steal a file) to completing the job based on the information in the request (e.g. They provide the IP, username, file to steal, and that populates the necessary script inputs).

## Network

The initial design behind the net for the player will be a node-style virtual map of the network, allowing for custom configurations of their own "base" as they build and expand their operations. This could be defined/stored in the custom yaml-style format used in the interface scripting (see below).

## Interface

A custom-designed scripting language will be used (similar to shell/bash/batch files) that allow the user to create unique payloads. Utilizing this will allow for packaging of these components to complete tasks available (deploy a bot, launch a virus, steal files/data, cripple a network, etc.) leveraging whatever creativity a user can come up with to build their attacks. Inversely, this could also be a potential option to allow them to build custom-designed defenses against other user attack scripts. Script execution paths can be defined with a yaml-style file

## Virtual Market?

There may be a potential to create a virtual marketplace to either allow for potential passive income by market buy/sell/manipulation or selling off excess hardware/software components. Successfully hacking corporations may result in affecting their virtual stock price (allowing further gains).


# Technical Implementation

## Scripting API

A verbose API will need to be developed that gives the user enough flexibility to call a series of endpoints that (given the proper input) know how to handle the inputs and output a success/failure and any associated data requested.

## Network Definition

A network definition file (YAML/JSON?) would allow for the user to create a custom network design of their creation and a consistent approach to storage of the network. This could be added to or adjusted based on purchases or other design decisions throughout the course of a game to allow for trial and error scenarios of varying types of networks.
