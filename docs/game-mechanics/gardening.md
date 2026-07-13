# Gardening

The Gardening system lets you grow and cross-pollinate a wide variety of decorative plants. Seeds are planted in pots, cared for over several days, and bred with other plants to unlock new varieties and color combinations. All fully grown plants are purely decorative, they exist to beautify your home and nothing more.

## Plant bowl

You can buy a Plant bowl from Provisioner NPCs.

1. Fill the bowl with 5 Fertile dirt.

2. Soften the dirt, two uses from a Pitcher of Water is enough.

3. Plant the seed.

Your plant is ready, it will only grow if locked down in a house or in your backpack.

### Fertile dirt

Fertile dirt can be found on the ground in the Ocllo Sewers.

Can also be looted from Boars, Bull Frogs, Giant Toads and Earth Elementals.

### Pitcher of Water

You can buy a Pitcher of Water from Provisioner NPCs.

It can be refilled using a Water Trough or Water barrel.

## Plant gump

![image](../assets/gumps/plant-bowl-gump.png)

??? note "Click to expand: Icons legend"

    === "Left side"

        - Top left corner: Growth stage
        - Reproduction page button
        - Insect infestation
        - Fungus infection
        - Poisoned
        - Diseased
        - Bottom left corner: Does nothing

    === "Right side"

        - Top right corner: Growth status
        - Water level
        - Add Greater Poison potions
        - Add Greater Cure potions
        - Add Greater Heal potions
        - Add Greater Strength potions
        - Bottom right corner: Empty bowl

## ![image](../assets/gumps/plant-growth-stage.png) Growth

A plant performs a growth check every 24 hours after you last tend it.

With each check, it advances through growth stages 1 to 9, shown by the icon in the top‑left corner.

On stage 7, the plant becomes visible and can both pollinate other plants and be pollinated.

On stage 9, the plant can be removed and set to decorative, or it can be left in place to continue producing seeds and resources.

### ![image](../assets/gumps/plant-growth-status.png) Growth status

The top right icon shows the plant's growth status.

   - A red exclamation mark means the plant is in an invalid spot. The growth check will fail, and nothing will change, the plant won't improve or decline.
   - A red dash means it didn't grow because it's unhealthy.
   - A yellow dash means the growth check hasn't happened yet.
   - A blue cross means the plant grew normally.
   - A green cross means the plant grew two stages.

## Maintenance

When a plant goes through a growth check, it may develop certain ailments. You need to remedy these before the next check so they don't end up harming the plant.

The icons on the left show what needs to be addressed before the next growth cycle.

The icons on the right let you add water or potions to remedy the ailments.

The bottom center displays the plant's Health, which has four stages: Vibrant, Healthy, Wilted, and Dying.

If the Health drops to Wilted or Dying apply two Greater Heal potions.

Applying ![](../assets/gumps/plant-strength-potion.png) Greater Strength potions can reduce how often a plant is affected by ailments.

### ![image](../assets/gumps/plant-water.png) Watering

If the water icon has no symbol, the plant has the perfect amount of water.

A yellow dash means you should water it once. A red dash means you should water it twice.

Be careful not to overwater, as it can harm the plant's health.

A yellow cross means the plant has been overwatered once and will need one growth cycle to recover. A red cross means it has been overwatered twice and will need two growth cycles to recover.

### ![image](../assets/gumps/plant-insect.png) Insect infestation

This can happen at random. If a yellow cross appears, apply one ![](../assets/gumps/plant-poison-potion.png) Greater Poison potion. If it's red, apply two.

### ![image](../assets/gumps/plant-fungus.png) Fungus infection

This can happen at random. If a yellow cross appears, apply one ![](../assets/gumps/plant-cure-potion.png) Greater Cure potion. If it's red, apply two.

### ![image](../assets/gumps/plant-poisoned.png) Poisoned

This happens when too many poison potions have been applied. A yellow cross means you should apply one ![](../assets/gumps/plant-heal-potion.png) Greater Heal potion. If it's red, apply two.

### ![image](../assets/gumps/plant-diseased.png) Diseased

This happens when too many cure potions have been applied. A yellow cross means you should apply one ![](../assets/gumps/plant-heal-potion.png) Greater Heal potion. If it's red, apply two.

### ![image](../assets/gumps/plant-bowl.png) Emptying the bowl

If you empty the bowl while the plant is still in its first growth stage, you'll get the seed back but lose the fertile dirt.

At any later stage, emptying the bowl will cause you to lose both the seed and the fertile dirt.

## ![image](../assets/gumps/plant-reproduction.png) Reproduction

![image](../assets/gumps/plant-reproduction-gump.png)

### ![image](../assets/gumps/reproduction-bowl.png) Bowl icon

This button brings you back to the plant gump.

### ![image](../assets/gumps/reproduction-decorative.png) Decorative

This icon appears only when the plant reaches stage 9 of growth.

Clicking it will convert the plant into a decorative item. Once set to decorative, the plant will no longer produce seeds or resources, and it will no longer require maintenance. At that point, it functions purely as decoration.

### ![image](../assets/gumps/reproduction-pollination-1.png) Pollination

This icon displays the pollination state.

   - A yellow dash means the plant isn't producing pollen yet.
   - A red cross means the plant can't produce pollen at all and cannot be cross‑pollinated.
   - A red exclamation mark means pollen is available.
   - A green cross means the plant has already been pollinated.

#### ![image](../assets/gumps/reproduction-pollination-2.png) Cross pollination

Click this icon to select another plant and perform cross‑pollination.

### ![image](../assets/gumps/reproduction-petals-1.png) Resources production

This icon shows the state of Resources production.

- A red cross means the plant produces no resources.
- A plant can produce up to eight resources in total.
- The number on the left shows how many resources are currently on the plant.
- The number on the right shows the current maximum, when harvested both number will decrease.
- When the right number reaches zero, the plant has produced all of its resources and won't generate any more.

#### ![Image](../assets/gumps/reproduction-petals-2.png) Harvest resources

Click this icon to harvester the resources.

### ![image](../assets/gumps/reproduction-seed-1.png) Seed production

This icon shows the state of Seed production.

- A red cross means the plant produces no seeds.
- A plant can produce up to eight seeds in total.
- The number on the left shows how many seeds are currently on the plant.
- The number on the right shows the current maximum, when harvested both number will decrease.
- When the right number reaches zero, the plant has produced all of its seeds and won't generate any more.

#### ![image](../assets/gumps/reproduction-seed-2.png) Harvest seeds

Click this icon to harvester the seeds.
