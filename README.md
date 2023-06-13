<h1>Tron Auto-Sweep</h1>

<p>Tron Auto-Sweep is a script written in JavaScript that allows for the automatic sweeping of TRX (Tron) funds from multiple source wallets to a destination wallet. It utilizes the TronWeb library to interact with the Tron blockchain.</p>

<h2>Features</h2>

<ul>
  <li>Supports multiple source wallet addresses with their corresponding private keys.</li>
  <li>Automatically checks the available balance of each source wallet.</li>
  <li>Transfers the funds to the specified destination wallet if there are available funds.</li>
  <li>Periodically performs the auto-sweeping process at regular intervals.</li>
</ul>

<h2>Prerequisites</h2>

<ul>
  <li>Node.js</li>
  <li>TronWeb library</li>
</ul>

<h2>Getting Started</h2>

<ol>
  <li>Clone the repository and navigate to the project directory.</li>
  <li>Install the required dependencies by running the following command:<br>
    <code>npm install</code></li>
  <li>Update the <code>wallets.csv</code> file with the details of your source wallets (one per line) in the format: <code>address,privateKey</code>.</li>
  <li>Modify the <code>destinationAddress</code> variable in the <code>auto-sweep.js</code> file to set your desired destination wallet address.</li>
  <li>Run the script using the following command:<br>
    <code>node auto-sweep.js</code></li>
</ol>

<h2>Configuration</h2>

<ul>
  <li>Modify the Tron network endpoint in the TronWeb instance setup to use the desired Tron network.</li>
  <li>Adjust the interval duration in the <code>setInterval</code> function to change the frequency of auto-sweeping.</li>
</ul>

<h2>Contributing</h2>

<p>Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.</p>

<h2>License</h2>

<p>This project is licensed under the <a href="LICENSE">Mozilla Public License 2.0</a>.</p>

<h2>Disclaimer</h2>

<p>Please note that the use of this script is at your own risk. Ensure that you have proper authorization and adhere to all legal and regulatory requirements when using it to manage Tron wallets and transfer funds.</p>

<h2>Acknowledgments</h2>

<ul>
  <li><a href="https://github.com/tronprotocol/tronweb">TronWeb</a> - JavaScript library for Tron blockchain interactions.</li>
</ul>
