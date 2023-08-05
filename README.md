# Architecture Revolution

This repository contains an advanced demo lesson where we evolve the architecture of a popular web application WordPress. The architecture journey starts with a manually built single instance, running the application and database. Throughout the stages of the demo, we will gradually evolve it into a scalable and resilient architecture.

## Stages

The demo is divided into 6 stages, each implementing additional components of the architecture:

1. **Stage 1** - Setup the environment and manually build WordPress.
2. **Stage 2** - Automate the build using a Launch Template.
3. **Stage 3** - Split out the database into RDS and update the Launch Template.
4. **Stage 4** - Split out the WordPress filesystem into EFS and update the Launch Template.
5. **Stage 5** - Enable elasticity via an Auto Scaling Group (ASG) & Application Load Balancer (ALB) and fix WordPress (hardcoded WPHOME).
6. **Stage 6** - Cleanup.

## Images

All images and diagrams related to the architecture evolution process can be found in the [images folder](https://github.com/mirik12/architecture-revolution/tree/main/images).

Feel free to explore the stages and the accompanying images to understand the gradual transformation of the architecture. If you have any questions or suggestions, please feel free to reach out!

Happy learning and building! 🚀
