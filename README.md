# Testing template for Misato SSG

1. Get Misato source

   ```sh
   git clone https://github.com/flyingcakes85/misato
   cd misato
   git checkout new-parser
   ```

2. Build source code

   ```sh
   cargo build
   ```

3. Get this repo
   
   Clone this repo somewhere outside the Misato folder
   ```sh
   git clone https://github.com/flyingcakes85/misato_test_site
   cd misato_test_site
   ```

4. Run build
   
   In the root of this repo, run this. Replace `path/to/misato` to the actual path where you cloned Misato earlier.
   ```sh
   path/to/misato/target/debug/misato build
   ```

   This should create a one page site at `target/`. Open the generated `index.html` file in you web browser.