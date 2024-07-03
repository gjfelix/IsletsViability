# Impact of oxygen and glucose availability on the viability and connectivity of islet cells: a computational study of reconstructed avascular human islets

Gerardo J. Félix-Martínez, Diana Osorio-Londoño and J. Rafael Godínez-Fernández

## Files

This repository will include the following files:

 - **Model files**:  files containing the implementation of the models of naked and avascular islets. Model files include geometries, parameters, meshes, boundary and initial conditions. Simulations can be directly reproduced by loading the model files into COMSOL.
   
    - **Naked islets**: Steady-state simulations of naked avascular islets with 1, 6 and 20 mM glucose and peripheral oxygen between 10 and 350 mmHg
      1. Islet_1_naked.mph
      2. Islet_2_naked.mph
      3. Islet_3_naked.mph
      4. Islet_4_naked.mph
      5. Islet_5_naked.mph
      6. Islet_6_naked.mph
    
    
    - **Encapsulated islets**: Simulations of encapsulated islets with 6 mM glucose and peripheral oxygen between 10 and 350 mmHg
	
      1. Islet_1_encapsulated_steadystate.mph
    
      2. Islet_2_encapsulated_steadystate.mph
    
      3. Islet_4_encapsulated_steadystate.mph
      4. Islet_1_encapsulated_timedependent.mph
      5. Islet_2_encapsulated_timedependent.mph
      6. Islet_4_encapsulated_timedependent.mph
    
 - **Islet architectures**: Architectures obtained from the reconstruction process using IsletLab. Architecture files contain six columns: 1: cell radius, 2: dummy column, 3: cell type (alpha: 11.0, beta: 12.0, delta: 13.0), 4-6: cell center coordinates (x, y and z, respectively).

    - Islet_1_reconstructed.txt
    - Islet_2_reconstructed.txt
    - Islet_3_reconstructed.txt
    - Islet_4_reconstructed.txt
    - Islet_5_reconstructed.txt
    - Islet_6_reconstructed.txt

 - **Connectivity files**: Adjacency matrices for and peripheral oxygen between 10 and 350 mmHg. 

    - Control islets (assuming 100% viability):

        1. Islet_1_control_connectivity_adjacency_matrix.txt

        2. Islet_2_control_connectivity_adjacency_matrix.txt
        3. Islet_3_control_connectivity_adjacency_matrix.txt
        4. Islet_4_control_connectivity_adjacency_matrix.txt
        5. Islet_5_control_connectivity_adjacency_matrix.txt
        6. Islet_6_control_connectivity_adjacency_matrix.txt

    - Simulated islets (1, 6 and 20 mM glucose and peripheral oxygen between 10 and 350 mmHg). One file per simulated case will be provided with name:

        - Islet_X_G_YmM_po2_Z_connectivity_adjacency_matrix.txt

        Where **X** indicate the islet number (1-6), **Y** the glucose concentration in mM  (1, 6 or 20) and **Z** represents the peripheral oxygen in mmHg (10, 30, 50, 70, 100, 160, 270 or 250).

