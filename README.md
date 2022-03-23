This is a group assignment to see how Git works when more than one person works on a project.

We are going to make a code that asks the user for input from the user about whether they have a sphere, a box or a pyramid. The code will then ask the user for the appropriate input to calculate the volume of the object and the surface of its shadow (so the surface of the circle, square or parallelogram--assume the largest projection for this case, and triangle).

You will be split in 4 teams. Create a new branch (i.e, other than the Main) and give it a unique, characteristic name (e.g., Team_1_branch, Team_2_branch etc).  


-- Team 1 needs to make a function sphere_surface that takes R as input and calculates the surface of a circle. The function should return the calculated surface area. Team 1 should then make another function sphere_volume that uses R and calculates the volume of the corresponding sphere. The function should return the calculated volume.

-- Team 2 needs to make a function box_volume that takes as input the three sides a, b, c of a box and calculates its volume. The function should return the calculated volume. Team 2 should then make another function box_surface that takes the largest possible combination of a, b and c to calculate the surface of a square/parallelogram. The function should return the calculated surface area.

-- Team 3 needs to make a function pyramid_volume that takes as input the length of the sides x, y and height h of the pyramid and calculates its volume. The function should return the calculated volume. Team 3 should then make another function triangle_surface that takes the h and the largest of x and y to calculate the surface area of the triangle. The function should return the calculated surface area.

--Team 4 will make the code that binds all other codes together! Team 4 will make a code that asks the user for input for: 
  - if they have a sphere, box or pyramid. 
  - depending on the input above, ask for the necessary input to calculate the volume and surface area.
  The code should then call the appropriate function and print an informative statement about the volume and surface area of the object.



-----How to proceed after writing things up in your branches:

1. Team 1 will commit and publish their branch. Check on the webbrowser, you should all then see a message that the current branch is published, and you can create a “Pull Request” and continue the collaboration in GitHub.	Team 1 should click on the button and check your GitHub. You should see under “Pull requests” that you have pushed the new branch, which is now ready to be compared with the Main. Click on the “compare and pull request button”. It should show you that the branches are able to merge (i.e., there are no potentially fatal conflicts with the Main branch). Go on to make a Pull request and give some information on what your change to the branch was.
Everyone should be able to see it, make comments if they want, and finally can agree to merge the branch with the Main. Merge your branch with the Main branch. Check out under “Code”. Your file with the functions is now part of the Main branch and can be used by everyone in the team. 

2. Team 2 will follow the above steps and make sure all functions are merged in the main branch: they should commit and publish their branch, make a pull request (it should show you that the branches are able to merge (i.e., there are no potentially fatal conflicts with the Main branch), give some information on what the change to the branch was etc. Check out under “Code”. The complete file with the functions and main code calling the functions should  now be part of the Main branch and can be used by everyone in the team.


3. Team 3 will do the same, and finally

4. Team 4 will do the same. At the end you should have one functional code that takes input from the user and gives them information about the surface area and volume of the different objects they may have at hand. 












