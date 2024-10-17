# Black-Scholes-Pricing-Model

![image](https://github.com/user-attachments/assets/91857133-506e-44c9-8e0b-35b72baaedcf)

Import numpy for mathematical operations. Matplotlib and Axes3D for 3d plots in matplotlib. Spicy.stats.norm is used for access to the cumulative distribution function which is essential for the black scholes formula.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/4db01e4a-2c70-47b7-8e4e-844b29fdb115)

This function is the black scholes formula Using current stock price, strike price, time to expiration, risk free interest rate and volatility of the stock.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/53a3a20b-e723-4ecd-aa8c-272440f3bfec)

This function creats the 3d surface plots to show the relation of volatility, stock prices and option prices for both put and call options.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/daf20822-f4eb-4cc2-a6ba-fce4e288613f)

this function handles the user input and the variables assigned to each input are used in the black scholes function to calculate the call and put options. It then calls the function used to generate the 3d surface plots to visualise the option prices for difference stock prices and volatilities. And in case of an invalid input an error is displayed in the console.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/12125448-14ce-457d-be65-900f49e56897)

This function ensures that the code is only being run when it is being executed directly and not imported as a module.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<b>(In future I hope to implement an interactive element to the code potentially a GUI and sliders using libraries like plotly to allow the user to adjust volatility or stock price using sliders to see how the option price changes )<b>
