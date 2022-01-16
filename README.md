# Visualization-Using-Principal-Component-Analysis-From-Scratch
Visualization of various data using Principal Component Analysis and t-SNE
Check [source code](https://github.com/schroscatt/Visualization-Using-Principal-Component-Analysis-From-Scratch/blob/main/pca.ipynb) which also includes explanation of the functions.
Check [report](https://github.com/schroscatt/Visualization-Using-Principal-Component-Analysis-From-Scratch/blob/main/report.pdf) to learn more about PCA, Visualization and t-SNE methods.



 - What you can find in the code and report
        
       PCA on MNİST DATA  
     1. 10 Sample Digit Images per Digit Class:
         * Figure 1. Sample Images 2. Generation of Eigenvectors
     
     * 2.1 Mean Digit Image 
		* Figure 2: Mean digit image
     
     * 2.2 Eigenvectors   
		*   Figure 3: Largest 100 eigenvectors.
     
     * 2.3 Eigenvalues  
		 * Figure 4: Scree plot (Largest 50 eigenvalues)
     
     3. PCA Visualization  
	     * Figure 5: MNIST projection (Largest 50 eigenvalues)
     
     5. t-Distributed Stochastic Neighbor Embedding (t-SNE): 
	     * Figure 6: t-SNE of MNIST
     
     6. Fundamentals of t-SNE: How does t-SNE work?
         * Step 1: Find the pairwise similarities
         * Step 2: Based on the pairwise similarities in the high dimensional    space, map the data to a low dimensional space.
         * Step 3: Use gradient descent based on Kullback–Leibler divergence    (also called relative entropy) to minimize the   
   difference between    p_ij (similarity in high dimensional space) and
   q_ij (similarity in    low dimensional space)
		* Parameters
     6. Reconstruction of Images Using PCA with Different Number of Eigenvectors 
     
	       * 6.1 MNIST DATA  
	      * Reconstruction with Different Dimensions
	         * Figure 7: Reconstruction of MNIST 6.1.2 Explained Variance Ratio
	         * Figure 8: MNIST - Explained Variance Ratio  
	     * Reconstruction of Image by Using Least Number of Eigenvectors
	        *  Figure 9: Reconstruction of 3
	      *  6.2 FASHION DATA
     
	     *  Reconstruction with Different Dimensions 
		     * Figure 10: Fashion Data Reconstruction
     
	     * Explained Variance Ratio 
		      * Figure 11: Fashion Variance Ratio
     
	     *  Reconstruction of Image by Using Least Number of Eigenvectors 
		      * Figure 12: Fashion Top Reconstruction
         
       PCA on HUMAN FACES  
     1. 10 Sample Digit Images per 10 Human Face Class:
         Figure 13: Human Face - Plot 2. Generation of Eigenvectors:
     
      * 2.1  Mean Human Face Image: Figure 14: Human Face - Mean
     
     *  2.2 Eigenvectors:   Figure 15: Human Face - Top 100 Eigenvectors
     
    *  2.3 Eigenvalues:   Figure 16: Human Face - Largest 50 Eigenvalues
     
     3. PCA Visualization:   Figure 17: Human Face - Projection to two
     
     4. t-Distributed Stochastic Neighbor Embedding (t-SNE): Figure 18: Human Face - t-SNE
     
     5. Reconstruction of Images Using PCA with Different Number of Eigenvectors					      
      * 5.1. Reconstruction with Different Dimensions
	    * Figure  19: Human Face - Reconstruction  
     * 5.2 Explained Variance Ratio
         * Figure 10: Human Face - Explained Variance Ratio  
    *  5.3 Reconstruction of Image by Using Least Number of Eigenvectors 
	     * Figure 10: Human Face Reconstruction with the elbow value
