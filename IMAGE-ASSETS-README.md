# Image assets for Research and Projects pages

These two page files are prepared to show one image per research topic and per project. Add your own illustrations at the paths below; the image files themselves are intentionally not included in this package.

## Research figures
Put these files in `assets/img/research/`:
- `meta-learning.jpg` — few-shot examples / meta-learning pipeline
- `riemannian-geometry.jpg` — curved manifold / geodesic
- `multimodal-learning.jpg` — image, text, and audio fusion
- `environmental-ai.jpg` — environmental map and forecasting time series
- `ai-robotics.jpg` — robotics perception, planning, and control
- `optimization.jpg` — optimization landscape / manifold trajectory

## Project figures
Put these files in `assets/img/projects/`:
- `air-pollution-forecasting.jpg` — city pollution and forecasting
- `rmaml.jpg` — Riemannian meta-learning / MAML concept
- `temporal-knowledge-graph.jpg` — knowledge graph and temporal forecasting
- `persianfarm.jpg` — ontology matching / semantic graph

## Suggested image format
- Landscape 16:9 aspect ratio, ideally 1200 × 675 pixels
- JPG or WebP; keep each image reasonably compressed
- Use original diagrams or images you have permission to publish

The pages use responsive card grids and `relative_url`, so they work with al-folio's `baseurl` configuration. If you choose `.webp`, update the corresponding filename in the Markdown page too.
