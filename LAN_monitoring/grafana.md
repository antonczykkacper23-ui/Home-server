<h2>Creating container for Grafana</h2>
<ol>
  <li>
    <h3>Setting up container:</h3>
      <h5>General settings</h5>
        <ul>
          <li>container ID</li>
          <li>Container name: Grafana</li>
          <li>Password</li>
        </ul>
      <p>
        screenshot:
        <img scr="./images/grafana_ct_general"/>
      </p>
      <h5>Template</h5>
      <p>Choosing standard debian container template</p>
      <p>
        screenshot:
        <img scr="./images/grafana_ct_template"/>
      </p>
      <h5>Disk</h5>
      <p>Setting disk space to 5GiB</p>    
      <p>
        screenshot:
        <img scr="./images/grafana_ct_disk"/>
      </p>
      <h5>CPU</h5>
      <p>Deafult settings (1 core)</p>
      <p>
        screenshot:
        <img scr="./images/grafana_ct_CPU"/>
      </p>
      <h5>RAM memory</h5>
      <p>Memory set to 1024MiB and swap to 512MiB</p>
      <p>
        screenshot:
        <img scr="./images/grafana_ct_RAM"/>
      </p>
      <h5>Network connection</h5>
      <ul>
        <li>default NIC</li>
        <li>static IPv4</li>
          <ul>
            <li>address: 10.0.x.241/24</li>
            <li>gateway: 10.0.x.1</li>
          </ul>
        <li>DHCP on IPv6</li>
      </ul>
      <p>
        screenshot:
        <img scr="./images/grafana_ct_network"/>
      </p>
      <h5>DNS</h5>
      <p>Set to local DNS server</p>
      <p>
        screenshot:
        <img scr="./images/grafana_ct_DNS"/>
      </p>
</ol>

