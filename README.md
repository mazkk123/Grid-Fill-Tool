# Polygon Transform Tool

A utility tool which allows maya users to easily move mesh components by typing in arithmetic or trigonometric operations
into a custom window. This tool works on both local and globalspaces which gives artists better mesh control.

## Instructions on loading the tool

- Extract the src, images and Videos folders into a current directory path on your machine
- Within the src folder find the file called transform_2.0.py
- This is the main tool script
- Open a local maya session and open the maya python editor
- Paste this script into the editor and run the tool
- Optionally, create a new shelf button
- Find the python tab in the shelf options
- Paste this script into the python tab in the shelf options.
- Click apply and OK and the tool will be operational in future
  maya sessions
  
## Instructions on using the tool

- The tool contains a limited user interface for easy artist application
- The 3 float fields represent transform fields for rotating, translating and scaling mesh
  components on a currently selected mesh within the maya viewport
- Input arithmetic operations into one of these fields to apply the relevant
  transformations on a specific axis
- Toggle the global on and off to apply transformations on either local or global
  mesh spaces
- Supported operations include '+', '-', '/' as well as trigonometric operations such
  as sin(n) etc.
- aggregate arithmetic and trigonometric operations are also supported by this tool.
  
## Further improvements
- Adding more complex mathematical operations into the tool capabilities to allow
  users to transform mesh components by any mathematical operations
- Being able to transform multiple mesh components at once using the tool
- Peformance and optimization

