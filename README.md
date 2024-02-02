# Multidisciplinary Project - Algorithm Simulator

## Overview

This repository contains the code for the simulator component of the CZ3004/SC2079 Multidisciplinary Project. It was built in React, Next.js, & TailwindCSS.

## Setup

```bash
npm install
```

Start the app by

```bash
npm run dev
```

The app will be running at `localhost:3000`

## How it works

1. Set the starting position of the robot at where you want it to be.
2. Add the obstacles and position the image at your desired side of the obstacle. 
3. Click on `Submit` to find the path. `Reset All` to clear the map and put the robot back to the starting position. `Reset Robot` resets the robot to the starting position without clearing the map.
4. Use the left and right arrow buttons to go through the path step by step to see how the algorithm is working.

<div align="center">
  <img src="/images/3.jpg" alt="Interface" width=350 >
</div>

### Things to note

- You can also add obstacles without a symbol card by choosing the 'None' option for the direction.
- If you think it's not going by the shortest path possible, you can tweak the various constraints and safeguards in the algorithm code.

The algorithm API server should be running at a specific address, which you will need to change in `BaseAPI.js`.

# Disclaimer

Our team is not responsible for any errors, mishaps, or damages that may occur from using this code. Use at your own risk. This code is provided as-is, with no warranty of any kind.

# Acknowledgements

This simulator is based upon a previous repository - [CZ3004-SC2079-MDP-Simulator](https://github.com/pyesonekyaw/CZ3004-SC2079-MDP-Simulator) - but with significant improvements and a more modern user interface.
