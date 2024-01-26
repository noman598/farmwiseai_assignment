Experimentation Results
Vegetation Classification
• The threshold-based vegetation classification provides an initial segmentation of vegetation from non-vegetation areas.
• Experimentation with more sophisticated machine learning models can improve classification accuracy.
Vegetation Polygon Generation
• Contour extraction and polygon generation successfully delineate vegetation regions.
• Handling both Polygon and MultiPolygon geometries ensures a robust representation of the vegetation cover.
Area Estimation
• The calculated areas for vegetation polygons contribute valuable quantitative information about the size and distribution of vegetation in the
image.
Width Analysis
• The width analysis algorithm effectively enhances the spatial representation of vegetation width.
• Adjustments to the kernel size and morphology operations may impact the results.
Composite Image
• The composite image provides an intuitive visualization of vegetation, aiding in navigation and interpretation.
• Further customization of visualization parameters can enhance the clarity of the composite image.
Observations
• The choice of threshold in vegetation classification significantly influences the results. Fine-tuning this parameter is essential for achieving
accurate classifications.
• Handling variations in geometry types is crucial for polygon generation. The code has been modified to address potential errors related to
geometry types.
• The width analysis algorithm's effectiveness may vary based on the characteristics of the vegetation in the image. Experimentation with
alternative algorithms may be considered.
