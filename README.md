On the "Jupyter Scripts" folder two jupyter files allow to run independently the model that optimizes the split of the boxes on the left and right columns (a_Left_right_box_split_model.ipynb) 
and the model that places the boxes along each column in order to minimize to time to accomplish the production plan for a given layer permutation (b_Box_placement_and_SA.ipynb).
In the second model, by changing the number of iterations on the SA parameters to a positive value, a simulated annealing algorithm tries to find the layer permutation that minimizes
production time.

In the "Outputs" folder several pdf files show the different outputs that we obtained for each model. 
