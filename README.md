# GD32F103R-GD32F207R-dev-board

This board can be used with the `GD32F103Rx` and the `GD32F207Rx` (Ethernet) MCU's. 

Please note that the crystal for the `GD32F207Rx` is `25MHz` and the crystal for the `GD32F103Rx` is `8MHz`.

The USB is power only.

The 2x13 header is pin compatible with the Orange Pi Zero and Raspberry Pi boards. 

<table>
	<tr><th colspan="6">2x13 Header</th></tr>

	<tr>
	<td colspan="2">3.3V PWR</td>
	<td>1</td>
	<td>2</td>
	<td colspan="2">5V PWR</td>
	</tr>

	<tr>
	<td>I2C0 SCA</td>
	<td>PB7</td>
	<td>3</td>
	<td>4</td>
	<td colspan="2">5V PWR</td>
	</tr>
	
	<tr>
	<td>I2C0 SCL</td>
	<td>PB6</td>
	<td>5</td>
	<td>6</td>
	<td colspan="2">GND</td>
	</tr>
	
	<tr>
	<td></td>
	<td>PA6</td>
	<td>7</td>
	<td>8</td>
	<td>PC10</td>
	<td>USART2 TX</td>
	</tr>
	
	<tr>
	<td colspan="2">GND</td>
	<td>9</td>
	<td>10</td>
	<td>PC11</td>
	<td>USART2 RX</td>
	</tr>
	
	<tr>
	<td>USART5 RX</td>
	<td>PC7</td>
	<td>11</td>
	<td>12</td>
	<td>PB10</td>
	<td></td>
	</tr>
	
	<tr>
	<td>USART5 TX</td>
	<td>PC6</td>
	<td>13</td>
	<td>14</td>
	<td colspan="2">GND</td>
	</tr>
	
	<tr>
	<td></td>
	<td>PB14</td>
	<td>15</td>
	<td>16</td>
	<td>PB15</td>
	<td></td>
	</tr>
	
	<tr>
	<td colspan="2">3.3V PWR</td>
	<td>17</td>
	<td>18</td>
	<td>PA13</td>
	<td>SWDIO</td>
	</tr>
	
	<tr>
	<td>SPI2 MOSI</td>
	<td>PB5</td>
	<td>19</td>
	<td>20</td>
	<td colspan="2">GND</td>
	</tr>
	
	<tr>
	<td>SPI2 MISO</td>
	<td>PB4</td>
	<td>21</td>
	<td>22</td>
	<td>PA11</td>
	<td></td>
	</tr>

	<tr>
	<td>SPI2 SCK</td>
	<td>PB3</td>
	<td>23</td>
	<td>24</td>
	<td>PA15</td>
	<td>SPI2 CS</td>
	</tr>
	
	<tr>
	<td colspan="2">GND</td>
	<td>25</td>
	<td>26</td>
	<td>PA14</td>
	<td>SWCLK</td>
	</tr>
</table>

<table>
	<tr><th colspan="3">1x13 Header</th></tr>
	
	<tr>
	<td>1</td>
	<td colspan="2">NC</td>
	</tr>

	<tr>
	<td>2</td>
	<td colspan="2">GND</td>
	</tr>
	
	<tr>
	<td>3</td>
	<td>PA14</td>
	<td>SWCLK</td>
	</tr>
	
	<tr>
	<td>4</td>
	<td colspan="2">GND</td>
	</tr>
	
	<tr>
	<td>5</td>
	<td>PA13</td>
	<td>SWDIO</td>
	</tr>
	
	<tr>
	<td>6</td>
	<td colspan="2">NRST</td>
	</tr>
	
	<tr>
	<td>7</td>
	<td>PA5</td>
	<td>DAC1</td>
	</tr>
	
	<tr>
	<td>8</td>
	<td>PA4</td>
	<td>DAC0</td>
	</tr>
	
	<tr>
	<td>9</td>
	<td>PC12</td>
	<td>UART4 TX</td>
	</tr>
	
	<tr>
	<td>10</td>
	<td>PD2</td>
	<td>UART4 RX</td>
	</tr>
	
	<tr>
	<td>11</td>
	<td colspan="2">NC</td>
	</tr>
	
	<tr>
	<td>12</td>
	<td>PA3</td>
	<td>ADC</td>
	</tr>
	
	<tr>
	<td>13</td>
	<td colspan="2">NC</td>
	</tr>
</table>

<table>
	<tr><th colspan="2">USART0 (ISP)</th></tr>
	
	<tr>
	<td>1</td>
	<td>GND</td>
	</tr>
	
	<tr>
	<td>2</td>
	<td>RX</td>
	</tr>

	<tr>
	<td>3</td>
	<td>TX</td>
	</tr>	
</table>

<table>
<head>
	<tr>
		<th colspan="2">LED's</th>
	</tr>
</head>
<tbody>
	<tr>
		<td>1</td>
		<td>PC0</td>
	</tr>
	<tr>
		<td>2</td>
		<td>PC2</td>
	</tr>
	<tr>
		<td>3</td>
		<td>PC3</td>
	</tr>
	<tr>
		<td>4</td>
		<td>3V3</td>
	</tr>	
</tbody>
</table>

<table>
	<tr><th colspan="4">2x7 Header</th></tr>
	
	<tr>
	<td>PB13</td>
	<td>1</td>
	<td>2</td>
	<td>NC</td>
	</tr>
	
	<tr>
	<td>PB11</td>
	<td>3</td>
	<td>4</td>
	<td>PB12</td>
	</tr>
	
	<tr>
	<td>PC4</td>
	<td>5</td>
	<td>6</td>
	<td>PC5</td>
	</tr>
	
	<tr>
	<td>PA1</td>
	<td>7</td>
	<td>8</td>
	<td>PA7</td>
	</tr>
	
	<tr>
	<td>PA2</td>
	<td>9</td>
	<td>10</td>
	<td>PC1</td>
	</tr>
	
	<tr>
	<td>GND</td>
	<td>11</td>
	<td>12</td>
	<td>GND</td>
	</tr>

	<tr>
	<td>3V3</td>
	<td>13</td>
	<td>14</td>
	<td>3V3</td>
	</tr>	
</table>

### GD32F207Rx (only)

<table>
<head>
	<tr>
		<th colspan="4">External-PHY</th>
	</tr>
</head>
<tbody>
	<tr>
		<td>RMII TXD1</td>
		<td>1</td>
		<td>2</td>
		<td>NC</td>
	</tr>
	<tr>
		<td>RMII TX_EN</td>
		<td>3</td>
		<td>4</td>
		<td>RMII TXD0</td>
	</tr>
	<tr>
		<td>RMII RXD0</td>
		<td>5</td>
		<td>6</td>
		<td>RMII RXD1</td>
	</tr>
	<tr>
		<td>RMII REF_CLK</td>
		<td>7</td>
		<td>8</td>
		<td>RMII CRS_DV</td>
	</tr>
	<tr>
		<td>MDIO</td>
		<td>9</td>
		<td>10</td>
		<td>MDC</td>
	</tr>
	<tr>
		<td>GND</td>
		<td>11</td>
		<td>12</td>
		<td>GND</td>
	</tr>
	<tr>
		<td>3V3</td>
		<td>13</td>
		<td>14</td>
		<td>3V3</td>
	</tr>		
</tbody>
</table>


[PayPal.Me Donate](https://paypal.me/AvanVught?locale.x=nl_NL)