# DNID-Project-2
Project Design Process
The design process for our game was a collaborative and iterative journey that began with brainstorming sessions to determine the core concept and mechanics. We started by identifying key game themes we wanted in the game, that is adapting from classisc fairy tale Revenge of the Lawn Gnomes published in 1995. It follows the story of Joe Burton, a young boy whose father has an intense passion for gardening competitions. Mr. Burton purchases two strange, grinning lawn gnomes to add to his collection of garden decorations. Joe quickly notices something off about the gnomes, nicknamed Hap and Chip. After their arrival, mysterious events begin to occur in the neighborhood. Gardens are destroyed, plants uprooted, and prized vegetables ruined. Suspicion initially falls on Joe and his mischievous best friend, but Joe starts to believe that the gnomes themselves are alive and responsible for the chaos. As the story unfolds, Joe discovers that the gnomes are indeed magical creatures who come alive at night, wreaking havoc for fun. With the help of his sister and some clever planning, Joe manages to confront the gnomes and outsmart them, returning them to their dormant, decorative state.
![image](https://github.com/user-attachments/assets/e0b2f954-1893-463e-ae7b-4785fcb5f1a0)


Division of Work
Each team member contributed to different aspects of the project:

Cassandra focused more on Story Adaptation and Narrative Design: Responsible for integrating the book’s themes into the game. She was mainly charged with the artistic design of the main menu and narrative introductions. There are specific scripts for all buttons in the main menu and artistic sprites that she originally made. She also made an introduction video on the main menu for players to debrief our adaptive stories. 

Yishui accomplished most Programming and key gameplay mechanism: checkpoint systems, engaging enemy AI, collider setup of floating objects, camera follow mechanism and Health Bar System.
Yishui also accomplished most of the Graphics and Level Design: Designed and implemented the visual assets, level layouts, and environment aesthetics. Inside our game, we browsed various websites to acquire different sprites to meet our goal, especially for the sprites of our background, floating platforms, player's animation movements, and Genmoe Enmeies' animations. Yishui implements these online sprites into the projects and makes them workable to meet our expectations.

Both of us did testing and Debugging mainly aimed at mechanism implementation and collider issues. In the mid of our build-in process, there were lots of bugs relating to object collisions and parameters of characters such as the attack range, player speed, and colliding issues when climbing and jumping. When the game production progresses to the later stage, more mechanism bugs appear；

Respawn Issues: Players did not reset correctly at checkpoints, requiring debugging in the checkpoint manager and player health scripts.

Enemy Rebirth: Enemies did not reset when players respawned, leading to inconsistencies in gameplay.

Collision Detection: Some traps and enemies failed to interact with the player correctly due to errors in the collision layers.

Here are some possible Solutions we made

Checkpoint Manager Refactoring: Redesigned the respawn logic to ensure the player and enemies reset correctly.

Debugging Scripts: Thoroughly tested and revised scripts like PlayerRespawn and EnemyAI to ensure functionality.

Layer Adjustments: Fixed collision layer settings in Unity to ensure proper interactions between game objects.

However, there are still a lot of bugs in the game that cannot be fixed, for example, in some scenes, players will not fall down and die even if they are floating in the air.

The game concept was decided based on team discussions about creating a balance between story-driven elements and engaging gameplay mechanics. We chose a 2D platformer format as it aligned with the narrative and allowed us to create visually rich levels and challenging gameplay. Key features like respawn mechanics and enemy rebirth were included to provide dynamic challenges and replayability.

Graphics, and Assets
Graphics
We designed most of the visual assets using tools like Adobe Photoshop and Aseprite, focusing on a pixel art style that matched the game’s tone. For the backgrounds and environment, we used a mix of custom-designed assets and free-to-use assets sourced from online libraries. We chose pixel arts because Pixel art assets are lightweight and load efficiently, making the game run smoothly even on lower-end devices. This decision was crucial to ensure accessibility for a wider audience. Some previous video games such as "Celest" and "Self." In this version of the game, audio assets were omitted mainly because of time Constraints: The focus of our project was on gameplay mechanics, level design, and visual storytelling. With limited time, we prioritized core features over creating or integrating sound effects and background music. Skill Specialization: Our team had limited experience with sound design and music composition. Rather than rushing to create subpar audio, we chose to exclude it entirely to maintain the quality of the overall experience.


If we had additional time, we would add:

New Levels and Enemies: Expanding the world with diverse environments and enemy types.
Enhanced Storytelling: Adding cutscenes and branching storylines for a richer narrative.
Power-ups and Abilities: Introducing power-ups to provide players with new strategic options.
Advanced AI: Creating smarter, more dynamic enemies to increase the challenge.

Asset Sources and Credits
Graphics:
Custom graphics created in Adobe Photoshop and Aseprite.
Additional background assets from [source name/link].
Sounds:
Sound effects from [source name/link].
Background music composed by [team member/composer name] or sourced from [source name/link].
Story: Adapted from [Insert Book Title Here] by [Author's Name].
Video Playthrough
The video playthrough of the game is available at:

YouTube: [Insert YouTube Link]
GitHub Directory: The MP4 file can be found in the GameDemo folder in our GitHub repository at [Insert GitHub Link].
Conclusion
This project was a rewarding learning experience that showcased the importance of teamwork, problem-solving, and adaptability. While there are always areas for improvement, we are proud of the game we created and the skills we developed during its creation. We look forward to using these lessons in future projects.
