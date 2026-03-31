# neural-networks-generative-ai-assignment
Machine learning hw week 10


PARt D Reflection


I learned that data augmentation is basically "gym for AI." By tilting, zooming, and shifting the MNIST digits, the model had a harder time during training, but it became much more robust. While the baseline model was faster to "memorize" the static images, the augmented model actually generalized better because it wasn't just looking for perfect pixel match—it was learning the actual shapes.

The biggest hurdle wasn't the code it was my machine. I ran into a brick wall with DLL initialization error because my local CPU lacked the AVX instructions modern TensorFlow requires. It wasnt worth spending the time trying to fix it, I switched to Google Colab instead.

These techniques are everywhere. In medical imaging, where you might only have a few hundred scans of a rare disease, data augmentation can "create" thousands of variations to train a more accurate diagnostic tool. Similarly, in self-driving cars, you can’t record every possible angle of a rainy street, so you use augmentation and generative AI to simulate those conditions, making the navigation systems much safer for the real world.
