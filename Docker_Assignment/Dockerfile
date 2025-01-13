# Choose the `bcb420-base-image` Docker as the base operating system
FROM risserlin/bcb420-base-image:winter2024-arm64

# Install DESeq2, enrichplot, and pheatmap libraries to the Docker image
RUN R -e 'BiocManager::install(c("DESeq2", "enrichplot"))'
RUN R -e 'install.packages("pheatmap")'