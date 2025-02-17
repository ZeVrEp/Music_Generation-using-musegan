# Music_Generation-using-musegan
Music generation is achieved using Generative Adversarial Networks (GANs), specifically the MuseGAN model, which is designed to generate music that corresponds to the identified emotions. The mood configurations have been defined in the generation module so as to change the parameters while generating the music, according to the mood as selected by the user. In this case; uplifting, meditation, nature inspired and bittersweet.
![musegan architecture](https://github.com/user-attachments/assets/ba72bfd2-7895-4f8e-a4ad-0bbf9ea959c4)

MuseGAN is a generative adversarial network designed for music generation, particularly for creating multi-track compositions. The model includes two main components: the generator and the discriminator. The generator is built with both a multitrack model and a temporal model. The multitrack model allows the generator to produce multiple musical tracks simultaneously, such as drums, bass, and melody, while the temporal model ensures that the generated music maintains a coherent time structure, preserving rhythms and timing. 

The input to the generator can include random noise vectors or structured latent representations, such as predefined mood configurations. 

The discriminator evaluates the generated music by distinguishing between real and fake tracks, guiding the generator to improve. 

The output of the generator is typically in the form of MIDI files, which correspond to different music categories (e.g., meditation, uplifting, nature-inspired, or bittersweet) based on the mood configurations. 
These outputs can be visualized through tools like piano rolls and time-vs-pitch graphs.

![uplifting music](https://github.com/user-attachments/assets/b0dc2899-73d0-4a17-8e32-527177ba1dbf)

![bittersweet music](https://github.com/user-attachments/assets/b7e5ba42-5fde-45db-80fc-156729c3de3f)

![nature inspired music](https://github.com/user-attachments/assets/9d8bcdf4-2100-4733-85e1-551625d68603)

![meditation_music](https://github.com/user-attachments/assets/fd743fdb-fbf0-4ffb-9e55-3c75d7e90a33)

