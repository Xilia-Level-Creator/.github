# Xilia Level Creator

Xilia is a concept of custom (community) level builder for PewPewLive.
It consists of GUI (or any other source of level "blueprint", like AI
level creator), XLA file format (that represents the "blueprint"), and
a Compiler, which converts XLA files into actual levels:

![General level creator workflow flowchart](https://jpcdn.it/img/7b7a27538b02a36c2147712384113720.png)

## Project progress

This is a very general roadmap:

- [ ] XLA File Format Specification
  - [ ] Base spec
  - [ ] Describing built-in presets/transforms
  - [ ] Docs for creating custom presets/transforms with Lua
- [ ] Examples of levels, expressed in XLA format *(list may be changed)*
  - [ ] Eskiv
  - [ ] Hexagon
  - [ ] Timebomb
- [ ] Compiler
  - [ ] Read, parse and basic validation of XLA files
  - [ ] Form some basic levels
  - [ ] Support for more presets/transforms
- [ ] Potentially creating GUI for level creator?
