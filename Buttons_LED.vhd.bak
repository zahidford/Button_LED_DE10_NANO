----------------------------------------------------------------------------------
-- Company: 
-- Engineer: 
-- 
-- Create Date: 07/24/2019 03:48:01 PM
-- Design Name: 
-- Module Name: Button_LED - Behavioral
-- Project Name: 
-- Target Devices: 
-- Tool Versions: 
-- Description: 
-- 
-- Dependencies: 
-- 
-- Revision:
-- Revision 0.01 - File Created
-- Additional Comments:
-- 
----------------------------------------------------------------------------------


library IEEE;
use IEEE.STD_LOGIC_1164.ALL;

-- Uncomment the following library declaration if using
-- arithmetic functions with Signed or Unsigned values
--use IEEE.NUMERIC_STD.ALL;

-- Uncomment the following library declaration if instantiating
-- any Xilinx leaf cells in this code.
--library UNISIM;
--use UNISIM.VComponents.all;

entity Button_LED is
generic(
Num_buttons : integer :=4);
Port (
Button_Push : in std_logic_vector(Num_buttons -1 downto 0);
Enable_Button : in  std_logic;
Led_Out : out std_logic_vector(Num_buttons -1 downto 0) );
end Button_LED;

architecture Behavioral of Button_LED is

begin

        Led_Out <= Button_Push when Enable_Button ='0' else (others =>'0');

end Behavioral;
