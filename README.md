This repository contains a project that synthesizes and verifies JSON data. The program generates random JSON objects of various depths and structures,
and verifies their integrity using a custom scanner and printer system.

Features
JSON Synthesis: Generates random JSON objects with nested dictionaries, lists, constants, and strings.
Custom Scanner and Printer: Implements a scanner to format and print JSON objects in a structured and readable format.
State Machine for Parsing: Uses a state machine to parse and handle JSON strings, numbers, booleans, and special characters.

How It Works
Synthesis Functions: The program includes several functions to synthesize different types of JSON data:

synth_dict: Creates a dictionary with random keys and values.
synth_list: Creates a list with random elements.
synth_const: Generates random constants (boolean, null, integer, or float).
synth_string: Selects a random string from a predefined list of funny strings.
Scanner and Printer: The scanner processes the JSON object and ensures it is printed in a readable format. It uses a stack to handle nested structures and maintains formatting consistency.

State Machine: A state machine is used to handle JSON parsing, including special cases for strings and numbers. This ensures that the JSON data is correctly interpreted and formatted
