# Neonatal-multimodal-parcellation
Neonate-specific parcellation created with dHCP dataset
The parcellation files of the paper "Multi-modal multi-resolution atlas of the human neonatal cerebral cortex based on microstructural similarity";

You need Connectome Workbench software to open the files (https://www.humanconnectome.org/software/connectome-workbench)


 *.border:  the border file of the parcellation 
	final_border_left (right).border     - manual parcellation
	 LocSim_(num)_left (right).border - the automatic parcellation with different resolutions)

border_32k_ave_left(right).func.gii : the border density map

final_rois_merge_left (right).func.gii      : the parcellation file of manual parcellation
label_LocSim_(num)_left (right).func.gii : the parcellation file of automatic parcellation with different sesolutions

MMD_ave_dist_left (right).shape.gii      : the averaged PCA-based distance map
MMD_ave_gradient_left (right).func.gii : the averaged gradient map from the distance map

Morph_left (right).shape.gii                    : the averaged map of 10 used MRI properties 
Morph_org_gradient_left (right).func.gii : the gradient map of 10 used MRI porpeties 

week-40_hemi*. surf.gii : dHCP 40-weeks surface template file
