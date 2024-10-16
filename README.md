# LXR-Management 🏢

**LXR-Management** combines both **lxr-bossmenu** and **lxr-gangmenu** into one powerful management resource using **lxr-menu** and **lxr-input**, now with SQL support for managing society funds!

---

## Dependencies 🔧

- [lxr-core](https://github.com/LXRCore/lxr-core)
- [lxr-smallresources](https://github.com/LXRCore/lxr-smallresources) (For the logs)
- [lxr-input](https://github.com/LXRCore/lxr-input)
- [lxr-menu](https://github.com/LXRCore/lxr-menu)
- [lxr-inventory](https://github.com/LXRCore/lxr-inventory)
- [lxr-clothing](https://github.com/LXRCore/lxr-clothing)

---

## Screenshots 📸

![image](https://i.imgur.com/9yiQZDX.png)
![image](https://i.imgur.com/MRMWeqX.png)

---

## Installation 🛠️

### Manual Installation

1. **Download the script** and place it in the `[lxr]` directory of your server.
2. **Import the SQL file** `lxr-management.sql` into your database.
3. **Edit** the `config.lua` file to set the coordinates for your boss/gang menu locations.
4. **Restart** the script or your server to apply changes.

---

## Database Setup ⚙️

> **IMPORTANT**:  
> You must manually create a column in your database for the society in the `bossmenu` table or gang in the `gangmenu` table if you are using custom jobs or gangs.
> 
> **NOTE**: The boss and gang information now share the same table for simplicity.

Here’s an example of what your database setup should look like:

![database](https://i.imgur.com/JZnEK4M.png)

---

## License 📄

    LXRCore Framework
    Copyright (C) 2024

    This program is free software: you can redistribute it and/or modify
    it under the terms of the MIT License.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

    You should have received a copy of the MIT License along with this program.

---

With **LXR-Management**, you can seamlessly manage both society and gang funds, simplify menu operations, and enjoy full SQL integration. Get ready to lead like never before!
