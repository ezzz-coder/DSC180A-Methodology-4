## About Me

**Name:** Edward Zhang

**Email:** [edz001@ucsd.edu](mailto:edz001L@ucsd.edu)

**Section:** D38
**Mentor:** Zhijian Liu

---

## Quarter 2 Project Brainstorm

**What is the most interesting topic covered in your domain this quarter?**  
I think the most interesting topic so far is diffusion models, which generate images and videos by learning to gradually remove noise from random data. I’m especially interested in how to make them more efficient, since generating a single image can take dozens of denoising steps and a lot of compute. Seeing how techniques like step reduction and caching can speed up generation without hurting quality has been really eye-opening.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I’d like to develop our own algorithm for making diffusion models more efficient, either faster or less resource-intensive, specifically on Apple silicon. Apple’s chips have a unified memory architecture that differs from typical GPU setups, so optimizations designed for NVIDIA hardware may not carry over directly. Exploring how to take advantage of that architecture could make high-quality generation more practical on consumer laptops.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
I would spend more time experimenting with my own ideas instead of focusing mainly on replicating a paper’s results. That said, the papers we read this quarter were a great source of inspiration and gave me a solid foundation to build on. Next quarter, I’d like to use that foundation to test new variations and see whether they improve on the original methods.

**What other techniques would you be interested in using in your project?**  
I’d be interested in borrowing ideas from speculative decoding, where a smaller, faster model drafts outputs that a larger model then verifies, and adapting that to the denoising steps of diffusion models. I’d also like to explore quantization, which reduces the precision of model weights to cut memory usage and speed up inference. Combining these techniques could make diffusion models much more efficient, especially on resource-constrained hardware like Apple silicon.
