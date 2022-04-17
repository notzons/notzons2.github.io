game.StarterGui:SetCore("SendNotification", {
    Title = "Loading...";
    Text = "Made by: zons";
    Icon = "";
    Duration = "2";
    callbakc = bindableFunction;
    Button1 = "Okay";
})

wait(0.7)

game.StarterGui:SetCore("SendNotification", {
    Title = "Keybind: T";
    Text = "Prediction is automatically set depending on your ping";
    Icon = "";
    Duration = "3";
    callbakc = bindableFunction;
    Button1 = "Okay";
})

-- MAIN LOCK
--// Configs
getgenv().Key = Enum.KeyCode.T 
getgenv().Hitbox = "Head" 
getgenv().Prediction = 0.1698
getgenv().PingBasedPrediction = true -- can be set to true/false 

--// string
loadstring(game:HttpGet("https://raw.githubusercontent.com/W3P0K4JWD9m6F3sUt/240294/main/Type2lockupdated"))()
