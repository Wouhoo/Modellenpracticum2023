# Modellenpracticum2023
Source code for the 2023 tumor cell migration model, plus additional stuff.

## Files in this repository:
- Modellenpracticum-2023-CC3D.zip: The final (2D) model made in CC3D.
- Modellenpracticum-2023-3d.zip: The stub of the 3D model, also in CC3D.
- Supplementary-videos-1.zip and Supplementary-videos-2.zip: A selection of movies showing the simulation in action.
- Python scripts R model.zip: The first alternative model from the discussion chapter; contains both the R and Python code.
- Hook-Based Protrusion Model.zip: The second alternative model from the discussion chapter.

## Supplementary videos additional information:
- Typical movement.mkv: This movie shows a typical example of a simulation, in this case of a strongly adhesive cell moving through
  a randomly aligned, dense network. 
- Pulse movement.mkv: This movie again shows typical cell movement, but this time with an "infra-red" view showing the concentration
  of attracting chemicals. We see that the cell follows the chemical pulses, as explained in the report.
- Funnel problem.mkv: This movie shows the funnel problem mentioned in the report; after moving into the funnel, the protrusions
  can't manage to pull the cell through, so it gets stuck.
- Bad pathfinding.mkv: This movie shows a limitation of the pulse model; after moving into the fiber "cage" just to the right,
  the cell should be able to squeeze through the bottom hole, but gets stuck because pulses don't spawn in that direction.
- Pore size too small.mkv: This movie shows what happens in a network where the pores are too small; the cell nucleus can't squeeze
  through a hole that small, so the cell gets stuck.
