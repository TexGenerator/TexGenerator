<div align="center">

# TexGenerator: Advancing High-Quality Texture Creation with Image-Guided Diffusion Models
## [arXiv Preprint]() | [Project](https://TexGenerator.github.io) 

</div>

<div  align="center">
    <a>
      <img src="./assets/demo.gif" alt="Logo" width="100%">
    </a>
  </div>
</p>
In this paper, we introduce TextureGenerator, an innovative framework aimed at producing high-quality, semantically consistent 3D texture maps using reference images. While text-based 3D texture generation has been widely studied, there are still challenges when using images as a supervisory signal for generating 3D textures, often resulting in unsatisfactory outcomes. Current methods mainly depend on pre-trained Text-to-Image (T2I) diffusion models along with the IP_Adapter style transfer model for texture creation. However, these approaches typically capture only a portion of the image's style features, making it difficult to accurately reproduce the texture details from the reference image, leading to lower quality results. To tackle these challenges, this paper proposes the TextureGenerator framework. The framework starts by utilizing a rapid personalization diffusion model based on the reference image, then modifies the conditional image in Canny ControlNet to align its line semantic distribution with the reference image, and finally incorporates a multi-view diffusion model to generate precise 3D textures that maintain both style and semantic consistency. Compared to the current state-of-the-art methods, TextureGenerator significantly enhances the similarity and quality of textures generated from reference images, providing strong support for the creation of realistic, high-quality 3D assets.

## 🚩 News
-  Paper and code coming soon, stay tuned! 🔥

## 📖 Citation
```bibtex
@article{TexGenerator,
  title={TexGenerator: Advancing High-Quality Texture Creation with Image-Guided Diffusion Models},
  author={},
  journal={arXiv preprint arXiv:},
  year={2024}
}
```
