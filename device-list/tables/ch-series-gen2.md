# CH Series 2nd Generation Mapping Table
<table>
    <tr>
        <th>DATA BYTE</th>
        <th>VALUE</th>
        <th>FUNCTION</th>
        <th>DISPLAY</th>
    </tr>
    <tr>
        <td>D0</td>
        <td>16</td>
        <td>REPORT ID</td>
        <td rowspan="12">-</td>
    </tr>
    <tr>
        <td>D1</td>
        <td>104</td>
        <td rowspan="5">FIXED HEADER</td>
    </tr>
    <tr>
        <td>D2</td>
        <td>1</td>
    </tr>
    <tr>
        <td>D3</td>
        <td>6</td>
    </tr>
    <tr>
        <td>D4</td>
        <td>35</td>
    </tr>
    <tr>
        <td>D5</td>
        <td>1</td>
    </tr>
    <tr>
        <td rowspan="6">D6</td>
        <td>1</td>
        <td>DISPLAY TEST</td>
    </tr>
    <tr>
        <td>2</td>
        <td>DISPLAY: CPU | TEMP. | POWER | USAGE | FREQ.</td>
    </tr>
    <tr>
        <td>3</td>
        <td>DISPLAY: CPU | TEMP. | POWER | USAGE | FAN</td>
    </tr>
    <tr>
        <td>4</td>
        <td>DISPLAY: GPU | TEMP. | POWER | USAGE | FREQ.</td>
    </tr>
    <tr>
        <td>5</td>
        <td>DISPLAY: PSU | TEMP. | POWER | USAGE | FAN</td>
    </tr>
    <tr>
        <td>6</td>
        <td>DISPLAY: PSU | TEMP. | POWER | USAGE | POWER</td>
    </tr>
    <tr>
        <td>D7</td>
        <td>0-255</td>
        <td rowspan="2">POWER CONSUMPTION <sup><code>U16</code></sup></td>
        <td rowspan="2">CPU</td>
    </tr>
    <tr>
        <td>D8</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D9</td>
        <td>0-1</td>
        <td>TEMPERATURE UNIT ˚C / ˚F</td>
        <td>ALL</td>
    </tr>
    <tr>
        <td>D10</td>
        <td>0-255</td>
        <td rowspan="4">TEMPERATURE <sup><code>F32</code></sup></td>
        <td rowspan="9">CPU</td>
    </tr>
    <tr>
        <td>D11</td>
        <td>0-255</td>
    </tr>
    <tr>
        <td>D12</td>
        <td>0-255</td>
    </tr>
    <tr>
        <td>D13</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D14</td>
        <td>0-100</td>
        <td>UTILIZATION</td>
    </tr>
    <tr>
        <td>D15</td>
        <td>0-255</td>
        <td rowspan="2">FREQUENCY <sup><code>U16</code></sup></td>
    </tr>
    <tr>
        <td>D16</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D17</td>
        <td>0-255</td>
        <td rowspan="2">FAN SPEED <sup><code>U16</code></sup></td>
    </tr>
    <tr>
        <td>D18</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D19</td>
        <td>0-255</td>
        <td rowspan="2">POWER CONSUMPTION <sup><code>U16</code></sup></td>
        <td rowspan="9">GPU</td>
    </tr>
    <tr>
        <td>D20</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D21</td>
        <td>0-255</td>
        <td rowspan="4">TEMPERATURE <sup><code>F32</code></sup></td>
    </tr>
    <tr>
        <td>D22</td>
        <td>0-255</td>
    </tr>
    <tr>
        <td>D23</td>
        <td>0-255</td>
    </tr>
    <tr>
        <td>D24</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D25</td>
        <td>0-100</td>
        <td>UTILIZATION</td>
    </tr>
    <tr>
        <td>D26</td>
        <td>0-255</td>
        <td rowspan="2">FREQUENCY <sup><code>U16</code></sup></td>
    </tr>
    <tr>
        <td>D27</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D28</td>
        <td>0-255</td>
        <td rowspan="2">POWER CONSUMPTION <sup><code>U16</code></sup></td>
        <td rowspan="11">PSU</td>
    </tr>
    <tr>
        <td>D29</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D30</td>
        <td>0-255</td>
        <td rowspan="4"> TEMPERATURE <sup><code>F32</code></sup></td>
    </tr>
    <tr>
        <td>D31</td>
        <td>0-255</td>
    </tr>
    <tr>
        <td>D32</td>
        <td>0-255</td>
    </tr>
    <tr>
        <td>D33</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D34</td>
        <td>0-100</td>
        <td>UTILIZATION</td>
    </tr>
    <tr>
        <td>D35</td>
        <td>0-255</td>
        <td rowspan="2">POWER CONSUMPTION <sup><code>U16</code></sup></td>
    </tr>
    <tr>
        <td>D36</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D37</td>
        <td>0-255</td>
        <td rowspan="2">FAN SPEED <sup><code>U16</code></sup></td>
    </tr>
    <tr>
        <td>D38</td>
        <td>1-255</td>
    </tr>
    <tr>
        <td>D39</td>
        <td>-</td>
        <td>- NOT USED -</td>
        <td rowspan="3">-</td>
    </tr>
    <tr>
        <td>D40</td>
        <td>0-255</td>
        <td>D1-D39 CHECKSUM <sup><code>U8</code> REMAINDER</sup></td>
    </tr>
    <tr>
        <td>D41</td>
        <td>22</td>
        <td>TERMINATION BYTE</td>
    </tr>
    <tr>
        <td>...</td>
        <td>...</td>
        <td>- NOT USED -</td>
        <td>...</td>
    </tr>
</table>
