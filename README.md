# Denoising Diffusion Probabilistic Models Papers
Papers club from the AI team in D-ID  - this time Diffusion Model(DM).

Diffusion Models were first introduced in [Deep Unsupervised Learning using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585). However, it took until [Generative Modeling by Estimating Gradients of the Data Distribution](https://arxiv.org/abs/1907.05600) (Song et al., 2019, Stanford University), and then [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) (Ho et al., 2020, Google Brain) who independently improved the approach.

A good explnantion on what are Diffusion Models and why they are intresting can be found in [Diffusion-Models Tutorial](https://youtu.be/cS6JQpEY9cs) (CVPR 2022).


מועדון קריאת מאמרים שלנו - כל ההרצאות בעיברית
| Title | Paper / Resource | Year | Why is it interesting? | Asignee | Recording | Slides |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Denoising Diffusion Probabilistic Models|[Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) | 2020 | <details><summary>read why</summary>high quality image synthesis results using diffusion probabilistic models, a class of latent variable models inspired by considerations from nonequilibrium thermodynamics.</details> |  [@talbenha](https://github.com/talbenha) |[zoom](https://us02web.zoom.us/rec/share/R5p0KNMKW9AnjKrHvjrEo46k2gpoXOmaXV_dJ8FyD7Zm8G4yyre1SylmcnJ01qbI.3yoDhbK0KEROJ8X-)(@NnH10JK)|[slides](https://docs.google.com/presentation/d/1Myw8u8xoiG4JnO1syU0rcTqSoE63B1taMLrE-BqHaf8/edit?usp=sharing) |
|The Annotated Diffusion Model |[The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion) |  | <details><summary>read why</summary></details> | [self-work]() | -- |--|
| Colorization, Inpainting, Uncropping, and JPEG restoration |[Palette: Image-to-Image Diffusion Models](https://arxiv.org/abs/2111.05826) |  2021 | <details><summary>read why</summary> A unified framework for image-to-image translation based on conditional diffusion models and evaluates this framework on four challenging image-to-image translation tasks, namely colorization, inpainting, uncropping, and JPEG restoration</details> | [@ArnoBen](https://github.com/ArnoBen) | [zoom](https://us02web.zoom.us/rec/share/3ONQQLxdh2w3OyoS9GeL0bJbsuLVxW1XVVS4yCR9VOisTqFsWfhwJJKktX_GAYlW.bJ5edL8pb_9Q3Np4) (6CbWY6e*) | [slides](https://docs.google.com/presentation/d/1R8-DW3L_FwUUXY0a8FwtCqJCsd6Y3-J6QbqmN42dN0I/edit?usp=sharing)|
|Rethinking Diffusion Models Design|[Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/abs/2206.00364) | 2020 |  <details><summary>read why</summary>Karras, the StyleGAN author is doing a back to the roots rethinking design choices of diffusion models, creating a well justified baseline archtecture</details>| [@orgoro](https://github.com/orgoro) |[zoom1](https://us02web.zoom.us/rec/share/XJMH-N_7sz5sW34DBO0CLJF8_9LxUOW-_b1gVMeZnz50kYcP01DmU9SHJvrXzwan.RLxzHQ9YdIHZN4Cv)(.m0gN7.?) [zoom2](https://us02web.zoom.us/rec/share/LrClL1TKLvDeWlcGE_R0_zAj17QDgC27LTbGKta9xmyK4neCrokPkXxOc265z1OX.OCw21NhiDvb1zsNo)(S^*c0ai3)|[slides](https://docs.google.com/presentation/d/1X2PjvIrGKnB54_SYwrIyKpT8OVuzuUxIQRdEIlQ0SLU/edit?usp=sharing)|
| Super-Resolution |[Image Super-Resolution via Iterative Refinement](https://arxiv.org/abs/2104.07636) | 2021 |<details><summary>read why</summary>high quality image synthesis results using diffusion probabilistic models, a class of latent variable models inspired by considerations from nonequilibrium thermodynamics.</details> | [self-work]() | -- | --|
| Classifier (+ Classifier-Free) Diffusion Guidance |[Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233)  & [Classifier-Free Diffusion Guidance](https://openreview.net/pdf?id=qw8AKxfYbI)|  2021| <details><summary>read why</summary> DM achieve image sample quality superior to the current SOTA GAN models by improving the U-Net architecture, as well as introducing classifier (+calssifier free) guidance </details> | [@talbenha](https://github.com/talbenha)|[zoom](https://us02web.zoom.us/rec/share/pGRapvE0uvOgB3SB7u98gmggi5cVgKVml1z2ekMFzQCHR5OGkqfy2d1pjAuO2fuV.g-kZDplzf60eM4fk)(?JS330&C)| [slides](https://docs.google.com/presentation/d/1He5Z0DAl79kyaqUIFrXq2R1EI2U0xCSEThRfHn_I3b0/edit?usp=sharing)|
| Text2Image | [ImageGen](https://arxiv.org/abs/2205.11487)| 2022| <details><summary>read why</summary> text-to-image synthesis</details> | [@alon.mengi]() |[zoom](https://us02web.zoom.us/rec/share/CUMYwy3f-Ae0iyOs4N_h7CJ2ScXQq7e_f2dLA_hJZjO0EkCqt7RUMpE-sRESPTOm.0xZ5sJ5nqgbAuaOA)(7hB61@CU)| [slides](https://docs.google.com/presentation/d/1Bcpnv4tJEDR0WjLwC9Jj15cxpb9TbXlj39VAKzF_FEM/edit?usp=sharing)|
| Efficient DM (Stable Diffusion) |[High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) | 2022| <details><summary>read why</summary> Apply DM in the latent space of powerful pretrained autoencoders to enable training on limited computational resources while retaining their quality and flexibility</details> | [@ShiraBaronn](https://github.com/ShiraBaronn) |[zoom](https://us02web.zoom.us/rec/share/gq5s__EVz3tE4fxpu3Dcndoebwhkr-rkNITnl-fUfznpeNGDrWgj7aFmc3nABfiA.piWaq3Ov_HhvsCK4)(U!+B+7g+)| [slides](https://docs.google.com/presentation/d/1XP-IK4082s8LmuYMYbVX-TLGE56mYfFiflQbzuQenrs/edit?usp=sharing)|
| Imagic |[Imagic: Text-Based Real Image Editing with Diffusion Models](https://arxiv.org/abs/2210.09276) | 2022 | <details><summary>read why</summary>Apply complex (e.g., non-rigid) text-guided semantic edits to a single real image</details> | [@Ganitk]() |[zoom](https://us02web.zoom.us/rec/share/5imGKTR1OGl8KHMulUGoU8ldHtKDhGQgF0VlmF-BM87W4MkN0lARflkadRWi7FhJ.3VDqP1kRVJkNBbYA)(%1x7WWl*)| [slides](https://docs.google.com/presentation/d/1Lou6q_HoQnqZCYApDs065YOGr0BIa4BObGUuimmQiAM/edit#slide=id.p)|
| Text2Video |[Imagen Video: High Definition Video Generation with Diffusion Models](https://arxiv.org/abs/2210.02303) | 2022 | <details><summary>read why</summary>a text-conditional video generation system based on a cascade of video diffusion models</details> | [@maysteinfeld]() |[zoom](https://us02web.zoom.us/rec/share/hPGuKHU79rh-elicCPdD2U08px7NcaTbtKcl37t8WHvQltDdGIcAZkXXA8fVxk92.Ac3rVELeUIT9Tjty)($Y=U45cT)| [slides](https://docs.google.com/presentation/d/1sWtJ2L4aT96RTKqqmvoPrmCBkt5V_dSbRTjUrCP9ze0/edit?usp=sharing)|
|TTS-Diffusion| [Grad-TTS: A Diffusion Probabilistic Model for Text-to-Speech](https://arxiv.org/abs/2105.06337) | 2021 | <details><summary>read why</summary>Text-to-speech model with score-based decoder producing mel-spectrograms by gradually transforming noise predicted by encoder and aligned with text input by means of Monotonic Alignment Search.</details> | [@amitay-nachmani](https://github.com/amitay-nachmani) |[zoom](https://us02web.zoom.us/rec/share/McRkTKqqQoUHG-ee2K_-h47t7JY3_ezU4kFyuwWdj9jsrnNB-qnFmTFkUJ5Kgh8N.QBVAqnMSAZWH6eYz)(@3yMN0gC)| [slides](https://docs.google.com/presentation/d/1mDEzpSseq4B9l-Ycy0tz8hEZiKPZsLDVIxZqwdFh6d0/edit?usp=share_link)|
| 3D Shape Synthesis |[LION: Latent Point Diffusion Models for 3D Shape Generation](https://arxiv.org/abs/2210.06978) | 2022 | <details><summary>read why</summary>Hierarchical Latent Point Diffusion Model for 3D shape generation. LION is set up as a variational autoencoder (VAE) with a hierarchical latent space that combines a global shape latent representation with a point-structured latent space.</details> | [@matan-feldman](https://github.com/matan-feldman) |[zoom](https://us02web.zoom.us/rec/share/n6_kLX5Bb9OAOaxEdBZ-pGH9hQai9silDQ5eNeX4xGtkPHABl6OdyN9CbuZUvbCY.gWl4I9yQFZNc7aLR)(q=v@4WYg)| [slides](TBD)|
| DreamFusion |[DreamFusion: Text-to-3D using 2D Diffusion](https://arxiv.org/abs/2209.14988) | 2022 | <details><summary>read why</summary>DreamFusion use a pretrained 2D text-to-image diffusion model to perform text-to-3D synthesis</details> | [@ShiraBaronn](https://github.com/ShiraBaronn) |[zoom](https://us02web.zoom.us/rec/share/TfU3aAfXmOARGDwvtUusS26QQfpyh_zsJ9tOFR-j3lfLLnE83gp3fyXGqi-VOGb8.ftweXHrHnZ1Fz1y5)(9gZqV*2Y)| [slides](https://docs.google.com/presentation/d/1Lz1aO21ip6pNJV8P1a0gb2Hh9DFJKqajYDM2zAhqJjE/edit?usp=sharing)|
| FMRI-to-Image with SD|[High-resolution image reconstruction with latent diffusion models from human brain activity](https://sites.google.com/view/stablediffusion-with-brain/) | 2023 | <details><summary>read why</summary>Reconstruct images from FMRI using stable diffusion</details> | [@Ganitk]() |[zoom](https://us02web.zoom.us/rec/share/jTC2CK8cMrclf1lXvZZy2CqKGkQbj7ZVqV5vjP4H6ctbONuX-qJ9ilNA3lA4SsE.QBINxsCr7DuE78rp)(B5J0vf?+)| [slides](https://docs.google.com/presentation/d/1q22Prgb05VjJnNXpRmE8Ji-xhHq8pjEHCBAymLZ39Ds/edit?usp=sharing)|
| Few cool papers :sunglasses:|[Control Net](https://arxiv.org/abs/2302.05543), [InstructPix2Pix](https://arxiv.org/abs/2211.09800), [DreamBooth](https://arxiv.org/abs/2208.12242), [Textual-Inversion](https://arxiv.org/abs/2208.01618), [Prompt-to-Prompt](https://arxiv.org/abs/2208.01626)| 2023 | <details><summary>read why</summary>Closing the seminar with 5 cool papers</details> | [@talbenha](https://github.com/talbenha) |[zoom](https://us02web.zoom.us/rec/share/P0gblPz8_HjczyllJhGS2DW2a4wJsZGqxUnBUZMazE4oHpiHb9jGtAMTgpSyfIGj.HzYVrEy3lmoBHQkw)(r+52hd5@)| [slides](https://docs.google.com/presentation/d/1AXWtP-2vIFGjEpVmXqVkfOta6aP_ZHFf4Ngqts04eKI/edit?usp=sharing)| 
