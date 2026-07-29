# New Plot Systems Rating

| Idea | Rating | Uniqueness | Scalability | Social | Freedom | Difficulty |
|-|-|-|-|-|-|-|
| [PlotSquared](https://github.com/IncomeMC/.github/blob/main/plot_system.md#1-plotsquared) | ⭐⭐⭐⭐ | ⭐ | ⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | Easy |
| [Skyblock](https://github.com/IncomeMC/.github/blob/main/plot_system.md#2-skyblock) | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐⭐ | Easy |
| [Plot Portals](https://github.com/IncomeMC/.github/blob/main/plot_system.md#3-plot-portals) | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | Medium |
| [Vertical Plots](https://github.com/IncomeMC/.github/blob/main/plot_system.md#4-vertical-plots) | ⭐⭐⭐ | ⭐⭐⭐  | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐| Medium |
| [Public + Private](https://github.com/IncomeMC/.github/blob/main/plot_system.md#5-public--private-plot-system) | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ | Hard |
| [Flat Land](https://github.com/IncomeMC/.github/blob/main/plot_system.md#6-flat-land) | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | Hard |
| [Pad System](https://github.com/IncomeMC/.github/blob/main/plot_system.md#7-pad-system) | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | Very Hard |

## 1. PlotSquared
The current system uses PlotSquared, where each player claims a plot in a world.
Players can merge up to 9 plots to increase their build area, allowing for larger generator systems and builds while still keeping everyone in the same world.
This makes it easy to visit other players and explore.

### Pros
- Everyone can visit and see other players' builds.
- Shared world feels active and populated.
- Familiar and easy-to-use plot system.
- Supports merging plots (up to 9) for larger builds.

### Cons
- Expansion is limited by surrounding plots and the 9-plot merge cap.
- Larger builds may not fit within the maximum plot size.
- Players often need to clear large amounts of terrain before building.
- Future expansion can be blocked if neighboring plots are already claimed.

## 2. Skyblock
The Skyblock system gives each player their own private island where they can build and expand freely.
Players starts with an island that includes a preset generator system. Users can design their own unique base.
Unlike PlotSquared, players are not limited by nearby claims, giving them more freedom to expand.

### Pros
- Players have their own private space without neighboring plots blocking expansion.
- Large amount of freedom for designing bases and farms.
- Easy to create massive builds and generator setups.
- Players can customize their island however they want.

### Cons
- Players cannot naturally see other people's builds while playing.
- The world can feel less active because everyone is separated.
- Large builds require a lot of manual block placing.
- New players may feel isolated compared to a shared plot world.

## 3. Plot Portals
The Plot Portals system keeps the idea of a shared plot world while removing the limitations of nearby plots.
Players exist in the same world/plot, but they can't see each other. You visit plots by jumping in the portal (that's located in the middle of your plot) and choosing the user you'd like to visit.
Players can like, favorite and share the plots that they've been to. The GUI will include a sorting system with "Most Views", "Most Likes", "Recent", "Oldest", and more.

### Pros
- Players can have much larger plots without worrying about neighbors blocking expansion.
- Keeps the feeling of a shared world with easy visiting.
- Players can showcase their builds and farms to others.
- No need for plot merging limitations.
- Allows for more competitions for highlighted spots or island icons.

### Cons
- Players may feel less connected since everyone has their own separate area.
- Requires more development work compared to a normal plot system.
- A confusing system, but new.

## 4. Vertical Plots
The Vertical Plots system changes the way players expand their builds by focusing on height instead of only expanding horizontally.
Players start with a basic plot floor and can unlock additional floors as they progress. Each floor can have its own purpose.

### Pros
- Players can expand their base without needing more land.
- Creates a sense of progression as new floors are unlocked.
- Each floor can have a different theme or purpose.
- Encourages creative farm designs, such as towers.

### Cons
- Horizontal building space is still limited.
- Very large builds may not fit the floor size.
- Players may prefer natural-looking builds instead of vertical structures.
- Can become repetitive if every player's base becomes a tower.
- Requires custom systems for unlocking and managing floors.

## 5. Public + Private Plot System
The Public + Private Plot system combines the social aspect of the PlotSquared with the freedom of private building areas.
Each player owns a public plot that can be seen and visited by everyone, where they can showcase builds, create shops, or interact with other players.
Players can also purchase a private plot that acts as their personal expandable area for farms or storage.

### Pros
- Keeps the community feeling of shared plots.
- Players can showcase their builds and interact with others.
- Private plots allow for larger builds without neighbors blocking expansion.
- Create a natural place for player shops and trading.
- Gives players more freedom by separating social areas from personal areas.

### Cons
- Requires players to manage 2 different plot areas.
- More complex system to a normal plot setup.
- Players may ignore public plots if there is not enough reason to use them.
- Pretty hard to code for optimization.

## 6. Flat Land
The Flat Land system gives players a large open world where they can claim their own piece of land and build freely.
Similar to land-claim systems used in survival servers, players can expand their claimed areas as they progress.
Instead of fixed plots, players have more control over the size and shape of their base.

### Pros
- Players have almost unlimited freedom when designing their base.
- No fixed plot sizes or merge limitations.
- Players can expand their land as they progress.
- Users can see claims via DynMap or other such plugins.
- Works well for larger builds.

### Cons
- Large numbers of claims can cause performance issues.
- Requires more advanced land management systems.
- Players may spread out too far, making the world feel empty.
- Balancing expansion costs can be difficult. (Ranks either free area or cheaper prices)
- Requires protection against abandoned or unused land taking up space.

## 7. Pad System
The Pad System introduces a modular way of building and expanding bases.
When buying a pad, players can choose from different presets, such as generator farm, storage area, or a completely empty pad.
Players can customize each pad by choosing its name, color, and settings to create their own unique base layout.

Larger and more advanced presets require more money to purchase, giving players a progression system where they can unlock bigger and more useful areas over time.
Each pad also has its own privacy settings, allowing players to control who can view, enter, or interact with that specific area.

### Pros
- Allows players to design their base in a modular way.
- Players can choose exactly what each area is used for.
- Presets make building easier while still allowing customization.
- Creates progression through unlocking bigger and better presets.
- Each pad can have its own name, color, and privacy settings.
- Keeps the existing plot system while adding more depth and customization.

### Cons
- Requires a large custom system to develop.
- Many pads with detailed settings could affect performace & storage.
- Balancing pad prices and sizes may be difficult. (No idea how ranks would work)
- Players may need time to understand the system.
- Presets require regular updates to stay interesting.
