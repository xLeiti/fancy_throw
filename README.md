# fancy_throw
experimental cs2 JT-bind to automate throwing utility a special trajectory 

No use of external macros or exec_async. We read the ingame time and use mouse_x for inputs.

Currently tweaked for the mirage triple molotov from ramp (first clip, but aim a bit higher: https://youtu.be/36kP9aFf340?si=87BeINn7HmfTZSiY)

## setup

1. Throw ```fancythrow.cfg``` into your ```game\csgo\cfg```-folder
2. ```exec fancythrow```

## usage

1. Line up
2. Press mouse1 (+attack)
3. Press p
4. Start moving your mouse around left and right until you hear the bip sound
5. Let go of p

# fthDemoExtension
A radialradio menu for inferno and mirage showing a demo of fancythrow.

## setup

1. Throw ```platform_english.txt``` into your ```game\csgo\resource```-folder
2. Throw the ```fthDemoExtension```-folder into your ```game\csgo\cfg```-folder
3. ```exec fthDemoExtension/main```

# usage

1. Type ```demoInferno``` or ```demoMirage``` into the console, depending which map you are on.
2. Press ```l``` to open the radialmenu and select the lineup you want to throw. (if you are practicing offline with sv_cheats 1, it will automatically teleport you to the right position)
   Selection: hover over the menu item and press ```l``` again
3. Perform the fancy throw according to the guide
