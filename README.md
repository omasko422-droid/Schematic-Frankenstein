# Schematic-Frankenstein
I frankensteined both from ocelarrisdesigns over on Tumblr (Schematic Designs and Sakura). Works well on both mobile and PC.
# Preview
! [Screenshot 2026-11-24 204244.png]

## How to Install on AO3

### 1. Create the Base Skin(s)
1. Log in to AO3 and go to **Dashboard > Skins > Create Site Skin**.
2. Choose whether you want the **Beige** or **Blue** schematic (or create both if you want automatic Light/Dark mode switching in Step 2).
3. Fill in the details:
   * **Title:** `[YourUsername] Beige Schematic` or `[YourUsername] Blue Schematic` *(Skin titles on AO3 must be unique!)*
   * **CSS:** Copy and paste the full CSS code for the theme you want.
4. Click **Submit** (or **Update**). If you are only using one theme, click **Use** and you're done!

---

### 2. Optional: Auto-Switch Between Light & Dark Mode
*Note: You must create **both** the Beige Schematic and Blue Schematic skins from Step 1 for this to work.*

1. Go back to **Create Site Skin** and make a third parent/wrapper skin:
   * **Title:** `[YourUsername] Schematic Default`
   * **CSS:** Copy and paste the following snippet:
     ```css
     .schematic {
       opacity: 1;
     }

     body,
     td,
     th,
     input,
     textarea,
     select,
     #workskin {
       font-family: "Bradley Hand", "Segoe Print", "Chalkboard SE", cursive;
     }
     ```
2. Scroll down to the **Advanced** section and click **Show**.
3. Under **Parent Skins**, add both `[YourUsername] Beige Schematic` and `[YourUsername] Blue Schematic`.
4. Click **Submit** to save `[YourUsername] Schematic Default`.
5. Now set the color scheme preference for each base skin:
   * Edit `[YourUsername] Beige Schematic` → open **Advanced** → set **Prefer Color Scheme** to **Light** → click **Update**.
   * Edit `[YourUsername] Blue Schematic` → open **Advanced** → set **Prefer Color Scheme** to **Dark** → click **Update**.
6. Return to your **Skins** page and click **Use** on `[YourUsername] Schematic Default` to activate automatic Light/Dark switching.
