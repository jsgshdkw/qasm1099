game.Players.LocalPlayer.Character.Humanoid.Health = 0
wait(0.5)
game.StarterGui:SetCore("SendNotification", {
    Title = "‼️‼️‼️‼️‼️ ";
    Text = " منور ابو السكربت   "; -- ARAB TEAM
    Duration = 5;
})
local args = {
    [1] = "RolePlayName",
    [2] = " مطور السكربت قاسم "
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
wait(0.1)
local args = {
    [1] = "RolePlayBio",
    [2] = "-------------"}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
wait(0.5)
game.StarterGui:SetCore("SendNotification", {
    Title = "صُنِعُ أَلْمَطْوٌرٌ قُآسِمً  ";
    Text = " تم تفعيل السكربت "; -- ARAB TEAM
    Duration = 5;
})
 
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Brookhaven198/-itachi-iraq/refs/heads/main/مال%20سايكو")))()
MakeWindow({
  Hub = {
    Title = "1.1V BETA سكربت قاسم | QASSEM SCRIPT",
    Animation = "🌀Welcome🌀  "
  },
  Key = {
    KeySystem = false,
    Title = "Key System",
    Description = "",
    KeyLink = "",
    Keys = {"1234"},
    Notifi = {
      Notifications = true,
      CorrectKey = "Running the Script...",
      Incorrectkey = "The key is incorrect",
      CopyKeyLink = "Copied to Clipboard"
    }
  }
})
 
MinimizeButton({
  Image = "rbxassetid://https://images.app.goo.gl/j3xta",
  Size = {50, 50},
  Color = Color3.fromRGB(255, 255, 255),
  Corner = true,
  Stroke = true,
  StrokeColor = Color3.fromRGB(255, 255, 255)
})
 
 
local Main = MakeTab({Name = "~حـسـابـاتـي~"})
local Image = AddImageLabel(Main, {
  Name = "قـاسـم",
  Image = "rbxassetid://115881843808544"
})
local Paragraph = AddParagraph(Main, {"حساباتي لل توصل معي لو تبون اي شي اضيفه لل سكربت", "bom dia meus manos"})
AddButton(Main, {
  Name = "~انـسـخ يـوزري تـيـك تـوك~",
  Callback = function()
    setclipboard('7bssn')
  end
})
 
AddButton(Main, {
  Name = "~حـسـابـي روبـلـوكـس~",
  Callback = function()
    setclipboard('jsgshdkw')
  end
})
 
AddButton(Main, {
  Name = "~قـناتي يوتيوب~",
  Callback = function()
    setclipboard('hyper_83')
  end
})
 
local Main6 = MakeTab({Name = "~الـمـعـلـومـات~"})
SetSection(AddSection(Main6, {"Coowner"}), "Owner : قُآسِمً")
 
local player = game.Players.LocalPlayer
SetSection(AddSection(Main6, {"UserId"}), "Player ID : ".. player.UserId)
 
local section = AddSection(Main6, {"Play Time"})
SetSection(section, "Play Time")
 
local startTime = tick()
spawn(function()
    while true do
        local playTime = tick() - startTime
        SetSection(section, "مدة اللعب: " .. math.floor(playTime / 60) .. " دقيقة و " .. math.floor(playTime % 60) .. " ثانية")
        wait(1)
    end
end)
 
 
local Main = MakeTab({Name = "~سـكـربـتات مـتـنوعـه~"})
 

AddButton(Main, {
  Name = "~r6 سكربت تحول~",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua"))()
  end
})

AddButton(Main, {
  Name = "~سكربت كيبورد~",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
  end
})

AddButton(Main, {
  Name = "~سكربت جميع رقصات~",
  Callback = function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/Baseplate-Fe-All-Emote-7386"))()
  end
})

AddButton(Main, {
  Name = "~سكربت تلمس الشخص تقتله~",
  Callback = function()
    loadstring(game:HttpGet('https://pastebin.com/raw/TXMNj1yy'))()
  end
})

AddButton(Main, {
  Name = "~سكربت جميع رقصات~",
  Callback = function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/Baseplate-Fe-All-Emote-7386"))()
  end
})
 
AddButton(Main, {
  Name = "~جميع المشيات في روبلكس~",
  Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-AFEM-14048"))()
  end
})

AddButton(Main, {
  Name = "~سكربت يمشيك ؏ هواء~",
  Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Float'))()
  end
})

AddButton(Main, {
  Name = "~سكربت fps120~",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت نسخ سكنـات~",
  Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-rochips-universal-18294"))()
  end
})
 
AddButton(Main, {
  Name = "~سـكربت جـل~",
  Callback = function()
    loadstring(game:HttpGet("https://pastefy.app/YZoglOyJ/raw"))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت الهلال~",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/n0kc/AtomicHub/main/Map-Al-Biout.lua"))()
  end
})
 

 
AddButton(Main, {
  Name = "~سكربت رحمة~",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/OMK/refs/heads/main/VR7-ON-TOP"))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت اختفاء اللاعب~",
  Callback = function()
    loadstring(game:HttpGet('https://pastebin.com/raw/3Rnd9rHf'))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت طيران كنبة~",
  Callback = function()
    loadstring(game:HttpGet('https://pastebin.com/raw/TXMNj1yy'))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت طيران قاسم~",
  Callback = function()
    loadstring(game:HttpGet("https://pastebin.com/raw/UnNbzLeq"))()
  end
})
 

 
AddButton(Main, {
  Name = "~سكربـت اغاني~",
  Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script'))()
  end
})

 
AddButton(Main, {
  Name = "~سكربت قفل~",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Sector9922/SECTOR-SHIFT-LOCK/main/SECTOR%20SHIFT%20LOCK"))()
  end
})


local Main = MakeTab({Name = "~سـكـربـت كـشـف~"})
AddButton(Main, {
  Name = "~سكربت كشف اسماء اللاعبين~",
  Callback = function()
 
loadstring(game:HttpGet('https://raw.githubusercontent.com/Lucasfin000/SpaceHub/main/UESP'))()
  end
})

 
local Main = MakeTab({Name = "~سـكـربـت مـركـبـات~"})
AddButton(Main, {
  Name = "~سكربت سرعه سياره~",
  Callback = function()
 
loadstring(game:HttpGet('https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script'))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت طيران السياره~",
  Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/njhh6U4w"))()
  end
})

AddButton(Main, {
  Name = "~سكربـت عاصفه سياره~",
  Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Projeto-LKB-I-Super-Ring-V3-I-Cracked-23346"))()
  end
})


local Main = MakeTab({Name = "~سكربت تجميع بيض~"})
AddButton(Main, {
  Name = "~سـكـربـت  تشغيل التجميع~",
  Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-EASTER-HUNT-EGG-WIN-35161"))()
  end
})



local Main = MakeTab({Name = "~سكربتات حمايـه~"})
AddButton(Main, {
  Name = "~سـكـربـت يـقـتـل الـنـاس ب كـنـبـه~",
  Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()
  end
})
 
AddButton(Main, {
  Name = "~سكربـت يطير اي احد يفعل علـيك~",
  Callback = function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-FE-Fling-GUI-10927"))()
  end
})
 
AddButton(Main, {
  Name = "~سكربـت محد يقدر يطيرك~",
  Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/ignore-touchinterests/main/main",true))() 
  end
})
 
 
local Main = MakeTab({Name = "~سكربت تخريب~"})
AddButton(Main, {
  Name = "~سكربت طيران كنبة~",
  Callback = function()
    loadstring(game:HttpGet('https://pastebin.com/raw/TXMNj1yy'))()
  end
})
 
AddButton(Main, {
  Name = "~سكربت قتل وسحب لاعب~",
  Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/SnoobG/Lua-Script-s/refs/heads/main/BrookHaven%20TvonHub'))()
  end
})

AddButton(Main, {
  Name = "~سكربت يطير ب ضربه ~",
  Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/0Ben1/fe/main/obf_rf6iQURzu1fqrytcnLBAvW34C9N55kS9g9G3CKz086rC47M6632sEd4ZZYB0AYgV.lua.txt'))()
  end
})
 


AddButton(Main, {
  Name = "~سكربت طيران اللاعب~",
  Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Auto%20Fling%20Player'))()
  end
})



local Main = MakeTab({Name = "~رؤوس ارجـل~"})
local Paragraph = AddParagraph(Main, {"الرؤوس", "bom dia meus manos"})
AddButton(Main, {
  Name = "~راس روبوت~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 3210773801
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "~راس المخفي~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "~راس رول-كوبي~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 746767604
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})

AddButton(Main, {
  Name = " ~راس عيون زرقاء~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 16580493236
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})
local Paragraph = AddParagraph(Main, {"~الارجل~", "bom dia meus manos"})
AddButton(Main, {
  Name = "~رجل مقطوع~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "~رجل العظام رصاصي~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 17500249989,
        [5] = 1,
        [6] = 1
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "~رجل العظام الاسود~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 14547162578,
        [5] = 1,
        [6] = 1
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "~رجل رول~",
  Callback = function()
    print("Clicked")local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 3230472745,
        [5] = 1,
        [6] = 1
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
  end
})







local Main = MakeTab({Name = "~الاجـسـام~"})
AddButton(Main, {
  Name = "~جسم بنت ايمو~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 96491916349570,
[2] = 76683091425509,
[3] = 75159926897589,
[4] = 1,
[5] = 1,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~جسم بنت خصر ضعيف~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 74302534603111,
[2] = 76683091425509,
[3] = 75159926897589,
[4] = 1,
[5] = 1,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
AddButton(Main, {
  Name = "~جسم بنت~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 96491916349570,
[2] = 14854350570,
[3] = 14854350451,
[4] = 1,
[5] = 1,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~جسم بنت يد صغيره~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 16214246112,
[2] = 16214249513,
[3] = 16214251181,
[4] = 1,
[5] = 1,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~جسم بنت الدلوعه~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 15539008532,
[2] = 15539008875,
[3] = 15539008680,
[4] = 15539008795,
[5] = 15539011945,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~جسم بنت صغير~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 14861800638,
[2] = 14861800626,
[3] = 14861801452,
[4] = 14861800627,
[5] = 14861801454,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
 
 
local Paragraph = AddParagraph(Main, {"~اجـسـام ولـد~"})
 
AddButton(Main, {
  Name = "~S15جســـم ولـد~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 17754346388,
[2] = 1,
[3] = 1,
[4] = 1,
[5] = 1,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~جسم ولد ضعيف~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 92757812011061,
[2] = 99519402284266,
[3] = 115905570886697,
[4] = 1,
[5] = 1,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~جسم ولد كوبي~",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 86499666,
[2] = 27112039,
[3] = 27112052,
[4] = 27112068,
[5] = 27112056,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
 
AddButton(Main, {
  Name = "✌🏻جسم ولد رول",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 27112025,
[2] = 27112039,
[3] = 27112052,
[4] = 3230472745,
[5] = 3230470862,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
 
AddButton(Main, {
  Name = "💪🏻جسم ولد معضل",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 18178775358,
[2] = 18178775182,
[3] = 18178775725,
[4] = 18178777453,
[5] = 18178775695,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
 
 
 
local Paragraph = AddParagraph(Main, {"🌜اجسام اقزام + هامستر🌛"})
 
AddButton(Main, {
  Name = "جـسـم الـقـزم",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 14579958702,
[2] = 14579959062,
[3] = 14579959191,
[4] = 14579959249,
[5] = 14579963667,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
end})
 
AddButton(Main, {
  Name = "جـسـم الـقـزم مـتـوسط ",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 77813057823038,
[2] = 135110043370135,
[3] = 116607813654019,
[4] = 138966229804486,
[5] = 128961183894053,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})

AddButton(Main, {
  Name = "جـسـم الـقـزم الـقـصـيـر",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 120973199097564,
[2] = 118345433416023,
[3] = 112849465115864,
[4] = 78321005147549,
[5] = 106586789635639,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
AddButton(Main, {
  Name = "جـسـم الـقـزم ",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 126267841602936,
[2] = 77530451194918,
[3] = 123471958406889,
[4] = 117042768644173,
[5] = 131948590344338,
[6] = 1
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})
AddButton(Main, {
  Name = "جـسـم الـهـامـسـتـر ",
  Callback = function()
print("Clicked")local args = {
[1] = "CharacterChange",
[2] = {
[1] = 14898536974,
[2] = 14898536957,
[3] = 14898537277,
[4] = 14898537300,
[5] = 14898537292,
[6] = 14898536975,
},
[3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
  end
})


local Main = MakeTab({Name = "الـسيـرفـر"})
AddButton(Main, {
  Name = "سكربت يعلق السيرفر",
  Callback = function()
tools = "FireX"
        shutdownserver = true
        if game.Players.LocalPlayer.Character.Humanoid.Sit == true then
            task.wait()
            game.Players.LocalPlayer.Character.Humanoid.Sit = false
        end
        if game:GetService("Workspace"):FindFirstChild("Camera") then
            game:GetService("Workspace"):FindFirstChild("Camera"):Destroy()
        end
        wait(0.1)
        if game:GetService("Workspace"):FindFirstChild("Camera") then
            game:GetService("Workspace"):FindFirstChild("Camera"):Destroy()
        end
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").WorkspaceCom["001_GiveTools"].FireX.CFrame + Vector3.new(0, -15, 0)
        task.wait(0.2)
        game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
        ddos = true
        for i = 1, 1350 do
            task.wait()
            if ddos == false then
                local args = {
                    [1] = "ClearAllTools"
                }
 
                cleartoolremote:FireServer(unpack(args))
                game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(9999, -475, 9999)
                return
            end
            if game:GetService("Workspace"):FindFirstChild("Camera") then
                game:GetService("Workspace"):FindFirstChild("Camera"):Destroy()
            end
            if game:GetService("Players").LocalPlayer.Character:FindFirstChild(tools) then
                game:GetService("Players").LocalPlayer.Character:FindFirstChild(tools):Destroy()
            end
            if ddos == false then return end
            fireclickdetector(game:GetService("Workspace").WorkspaceCom["001_GiveTools"].FireX.ClickDetector, 0)
        end
        game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, -475, 0)
  end
})
AddButton(Main, {
  Name = "سكربت تخريب العالم ",
  Callback = function()
    game.Workspace:ClearAllChildren()
  end
})

AddButton(Main, {
  Name = " 💫اعـادة دخـول الـى سـيرفـر",
  Callback = function()
    local ts = game:GetService("TeleportService")
				local p = game:GetService("Players").LocalPlayer
				ts:Teleport(game.PlaceId, p)
    print('Hello!')
  end
})

AddButton(Main, {
  Name = "سكربت جـودة اللعبه",
  Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Rtx-graphics-25102"))()
  end
})

AddButton(Main, {
  Name = "سكربت ازالة لاق ",
  Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
  end
})


 
local Main = MakeTab({Name = "🌟سـكـنـات🌟"})
local Paragraph = AddParagraph(Main, {"⭐حذف كل الاشياء الي في اليد⭐"})
AddButton(Main, {
  Name = "💫حذف كل الاشياء الي في اليد💫",
  Callback = function()
    local args = {
    [1] = "ClearAllTools"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clea1rTool1s"):FireServer(unpack(args))
  end
})
 
local Paragraph = AddParagraph(Main, {"✨سكنات بنات✨"})
 
AddButton(Main, {
  Name = "👩سكن بنت رقم [1]👩",
  Callback = function()
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 96491916349570,
        [2] = 76683091425509,
        [3] = 75159926897589,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15701713751
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 18509805623
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 18744734552
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15222846056
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 101459562936324
} 

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 17529187838
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 130491506065838
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 17444483167
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 16709737106
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15395115525
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 14762227337
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(5.0)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 96491916349570,
        [2] = 76683091425509,
        [3] = 75159926897589,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(3.7)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 3210773801
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 7581474755
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 6174066797
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "skintone",
    [2] = "Institutional white"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})

AddButton(Main, {
  Name = "~سكن بنت حلو رقم [2]~",
  Callback = function()
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 96491916349570,
        [2] = 76683091425509,
        [3] = 75159926897589,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13307477554
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15795056785
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 12563952028
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 11156841853
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 17744851762
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 16139700318
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13133257230
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 116091391891300
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13620518518
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(5.0)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 96491916349570,
        [2] = 76683091425509,
        [3] = 75159926897589,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(3.7)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 3210773801
    },
    [3] = "Roblox20"
}


game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 18510929286
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 7675094321
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "skintone",
    [2] = "Institutional white"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})
 
 
AddButton(Main, {
  Name = "~سكن بنت رقم [3]~",
  Callback = function()
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 96491916349570,
        [2] = 76683091425509,
        [3] = 75159926897589,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 73569970599873
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 71333952559271
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 129864383052397
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 17744851762
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 122223238457929
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 88966032649180
}


game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 127228549233812
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 9151422607
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 18923672769
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 137160650691565
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 6238758375
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 14402624573
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13900309877
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(5.0)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 96491916349570,
        [2] = 76683091425509,
        [3] = 75159926897589,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(3.7)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 3210773801
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 5981620229
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13329302128
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "skintone",
    [2] = "Institutional white"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})

local Paragraph = AddParagraph(Main, {"~سـكنات ولـد~"})
 
AddButton(Main, {
  Name = "~سـكن تنـين ازرق رقـم [1]~",
  Callback = function()
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 4637265517,
        [2] = 99519402284266,
        [3] = 115905570886697,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 14808924884
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15848163279
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 16127830905
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15535076528
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13575374227
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 11984960300
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 6433477241
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 14659003969
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 7667832719
} 

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(5.0)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 4637265517,
        [2] = 99519402284266,
        [3] = 115905570886697,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(3.7)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 3210773801
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "skintone",
    [2] = "Institutional white"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})

AddButton(Main, {
  Name = "~ســـكن غـوجـو رقـم [2]~",
  Callback = function()
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 4637265517,
        [2] = 99519402284266,
        [3] = 115905570886697,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
local args = {
    [1] = "wear",
    [2] = 91078281931212
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15581867745
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 15188738427
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 121979595367770
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(5.0)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 4637265517,
        [2] = 99519402284266,
        [3] = 115905570886697,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(3.7)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 1
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "skintone",
    [2] = "Institutional white"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
}) 

AddButton(Main, {
  Name = "~سـكن ولـد S15 رقـم [3]~",
  Callback = function()
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 139607718,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 17754346388,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
local args = {
    [1] = "wear",
    [2] = 140150480026352
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 82992820037885
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 13498671093
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 17386216598
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 14774768752
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 81526836860931
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 14832120928
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 5727822995
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 18594685747
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 18693879614
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(5.0)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 17754346388,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 1
    },
    [3] = "YinHub"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(3.7)
 
local args = {
    [1] = "CharacterChange",
    [2] = {
        [1] = 1,
        [2] = 1,
        [3] = 1,
        [4] = 1,
        [5] = 1,
        [6] = 134082579
    },
    [3] = "Roblox20"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Avata1rOrigina1l"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 83289659312825
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "wear",
    [2] = 12249790024
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(0.1)
 
local args = {
    [1] = "skintone",
    [2] = "Institutional white"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})


local Main = MakeTab({Name = "~الاسـمـاء~"})
local section = AddSection(Main, {"~اسماء بنات~"})
 
AddButton(Main, {
  Name = "زهراء",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "زهہرآء"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "فاطمه",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "فآطمہهہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "مايا",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "مہآيہآ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "ايات",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "آيہآتہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "رفل",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "رفلَ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "ضحى",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "ضہحہى"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "ليلى",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "لَيہلَى"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "زينب",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "زيہنہبہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "اديان",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "آديہآنہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "نرجس",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "نہرجہسہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "ابيان",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "اآبہيہآنہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "بتول",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "بہتہؤُلَ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "زهراء",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "زهہرآء"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "نور",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "نہؤُر"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
local section = AddSection(Main, {"~اسماء اولاد~"})
AddButton(Main, {
  Name = "رضا",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "رضہآ!"
}
 
AddButton(Main, {
  Name = "عمار",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "عہمہآر"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "يوهان",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "يہؤُهہآنہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "حسين",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "حہسہيہنہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "حسوني",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "حہسہؤُنہيہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "جعفر",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "جہعہفر"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "محمد",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "مہحہمہد"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "يوهان",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "يہؤُهہآنہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})

AddButton(Main, {
  Name = "صادق",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "صہآدق"
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})

AddButton(Main, {
  Name = "قاسم",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "قآسہمہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "علي",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "عہلَيہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "براهيم",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "بہرآهہيہمہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "هشام",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "هہشہآمہ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "بلال",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "بہلَآلَ"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "مرتضى",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "مہرتہضہى"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "منتظر",
  Callback = function()
    local args = {
    [1] = "RolePlayName",
    [2] = "مہنہتہظہر"
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1RPNam1eTex1t"):FireServer(unpack(args))
  end
})




local Main = MakeTab({Name = "~الــشـعــر~"})
 
local Paragraph = AddParagraph(Main, {"~دمـج شعر اولـاد~"})
 
AddButton(Main, {
  Name = "~اضـغط لـدمـج الاسـود~",
  Callback = function()
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 14808924884
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15848163279
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 16127830905
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15535076528
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~اضــغط لـدمـج البـني~",
  Callback = function()
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 14627143022
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15294036713
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15847969469
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15971158257
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})
 
AddButton(Main, {
  Name = "~اضـغط لـدمـج الابيــض~",
  Callback = function()
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 14627127264
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15908583844
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 14808889186
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
wait(1.0)
 
local args = {
    [1] = "wearWalkStyle",
    [2] = 15349539978
}
 
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r"):FireServer(unpack(args))
 
  end
})


local Main = MakeTab({Name = "~تـــنـــقـــل~"})
 
local section = AddSection(Main, {"~اختار اسم الاعب الي تبي تروح عنده~"})
 
local plrs = game.Players
 
-- Fetch all player names
local playerNames = {}
local players = plrs:GetPlayers()
 
for _, player in ipairs(players) do
    table.insert(playerNames, player.Name)
end
 
local Dropdown = AddDropdown(Main, {
  Name = playerNames[1] or "No Players",
  Options = playerNames,
  Default = "2",
  Callback = function(selectedplrName)
    plrs:FindFirstChild(selectedplrName)
        local targetPlayer = plrs:FindFirstChild(selectedplrName)
        if targetPlayer and targetPlayer.Character and targetPlayer.Character:FindFirstChild("HumanoidRootPart") then
            -- Teleporting your character to the selected player's position
            local targetPosition = targetPlayer.Character.HumanoidRootPart.Position
            local localPlayerRoot = plrs.LocalPlayer.Character:FindFirstChild("HumanoidRootPart")
 
            if localPlayerRoot then
                localPlayerRoot.CFrame = CFrame.new(targetPosition)
            end
        end
        print(selectedplrName)
 
  end
})
AddButton(Main, {
  Name = "~تـنـقـل~",
  Callback = function()
    mouse = game.Players.LocalPlayer:GetMouse() 
 
tool = Instance.new("Tool") 
 
tool.RequiresHandle = false 
 
tool.Name = "~اداة تنقل~" 
 
tool.Activated:connect(function() 
 
local pos = mouse.Hit+Vector3.new(0,2.5,0) 
 
pos = CFrame.new(pos.X,pos.Y,pos.Z) 
 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos 
 
end) 
 
tool.Parent = game.Players.LocalPlayer.Backpack
  end
})
local Slider = AddSlider(Main, {
  Name = "~مــــسـافة تــنـقـل~",
  MinValue = 10,
  MaxValue = 50,
  Default = 25,
  Increase = 1,
  Callback = function(Value)
 
  end
})
 
-- Function to teleport to Teleport
local function teleportToGasStation()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(192, 4, 272)
end
 
AddButton(Main, {
    Name = "~خلف البيت~",
    Description = "",
    Callback = teleportToGasStation
})
 
-- Function to teleport to Teleport
local function teleportToCenter()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(136, 4, 117)
end
 
AddButton(Main, {
    Name = "~امام البيت~",
    Description = "",
    Callback = teleportToCenter
})
 
-- Function to teleport to Criminal
local function teleportToCriminal()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-119, -28, 235)
end
 
AddButton(Main, {
    Name = "~مخزن الأسلحة~",
    Description = "Teleporta para as coordenadas do Criminal",
    Callback = teleportToCriminal
})
 
-- Function to teleport to House Abandoned
local function teleportToHouseAbandoned()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(986, 4, 63)
end
 
AddButton(Main, {
    Name = "~بـيـت مـسـكون~",
    Description = "Teleporta para as coordenadas da Casa Abandonada",
    Callback = teleportToHouseAbandoned
})
 
-- Function to teleport to Portal Agency
local function teleportToPortalAgency()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(672, 4, -296)
end
 
AddButton(Main, {
    Name = "~الـمـكان الــسـري~",
    Description = "Teleporta para as coordenadas do Portal da Agência",
    Callback = teleportToPortalAgency
})
 
-- Function to teleport to Brooks Diner
local function teleportToBrooksDiner()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(161, 8, 52)
end
 
AddButton(Main, {
    Name = "~الـكـافـي~",
    Description = "Teleporta para as coordenadas do Brooks Diner",
    Callback = teleportToBrooksDiner
})
 
local function teleportToBrooksDiner()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-26, 4, -23)
end
 
AddButton(Main, {
    Name = "~الـسـبـون~",
    Description = "Teleporta para as coordenadas do Brooks Diner",
    Callback = teleportToBrooksDiner
})
-- Function to teleport to Hospital
local function teleportToHospital()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-309, 4, 71)
end
 
AddButton(Main, {
    Name = "~الـمـستـشـفـى~",
    Description = "Teleporta para as coordenadas do Hospital",
    Callback = teleportToHospital
})
 
-- Function to teleport to Arch
local function teleportToArch()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-589, 141, -59)
end
 
AddButton(Main, {
    Name = "~فـوق الـجـسر~",
    Description = "Teleporta para as coordenadas do Arco",
    Callback = teleportToArch
})
 
-- Function to teleport to Agency
local function teleportToAgency()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(179, 4, -464)
end
 
AddButton(Main, {
    Name = "~مـكـان الـكـهـربـاء~",
    Description = "Teleporta para as coordenadas da Agência",
    Callback = teleportToAgency
})
 
-- Function to teleport to Hotel Center
local function teleportToHotelCenter()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(182, 4, 150)
end
 
AddButton(Main, {
    Name = "~البيوت~",
    Description = "Teleporta para as coordenadas do Centro dos Hotéis",
    Callback = teleportToHotelCenter
})
 
-- Function to teleport to Secret Room in Workshop
local function teleportToSecretRoomInWorkshop()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 4, -495)
end
 
AddButton(Main, {
    Name = "~تحيات الارض~",
    Description = "Teleporta para as coordenadas da Sala Secreta na Oficina",
    Callback = teleportToSecretRoomInWorkshop
})
 
-- Function to teleport to Secret Room 2
local function teleportToSecretRoom2()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-343, 4, -613)
end
 
AddButton(Main, {
    Name = "~تـحـت الارض~",
    Description = "Teleporta para as coordenadas do Local Secreto",
    Callback = teleportToSecretLocation
})
-- Function to teleport to Island 1
local function teleportToIsland1()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1925, 23, 127)
end
 
AddButton(Main, {
    Name = "~تـحـت الارض~",
    Description = "Teleporta para as coordenadas da Sala Secreta 2",
    Callback = teleportToSecretRoom2
})
-- Function to teleport to Secret Location
local function teleportToSecretLocation()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(505, -75, 143)
end
 
AddButton(Main, {
    Name = "~الـمـطـار~",
    Description = "Teleporta para as coordenadas do Aeroporto",
    Callback = teleportToAirport
})
 
-- Function to teleport to Lower Houses
local function teleportToLowerHouses()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(63, 35, 410)
end
 
AddButton(Main, {
    Name = "~الـجـزيـرة~",
    Description = "Teleporta para as coordenadas da Ilha 1",
    Callback = teleportToIsland1
})
 
-- Function to teleport to Airport
local function teleportToAirport()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(310, 5, 31)
end
 
AddButton(Main, {
    Name = "~فـي الـشـارع~",
    Description = "Teleporta para as coordenadas das Casas Inferiores",
    Callback = teleportToLowerHouses
})
 
-- Function to teleport to On Top of School
local function teleportToOnTopOfSchool()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-370, 50, 173)
end
 
AddButton(Main, {
    Name = "~فـوق الـمـدريـة~",
    Description = "Teleporta para as coordenadas Em Cima da Escola",
    Callback = teleportToOnTopOfSchool
})
 
-- Function to teleport to Mountain 1
local function teleportToMountain1()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-670, 251, 765)
end
 
AddButton(Main, {
    Name = "~فـوق الـجـبل~",
    Description = "Teleporta para as coordenadas da Montanha 1",
    Callback = teleportToMountain1
})
 
 
 
local Main = MakeTab({Name = "~جيمباسات الـسـيـارة~"})
local Paragraph = AddParagraph(Main, {"~ادخـل كـود الاغنـيه~"})
 
AddTextBox(Main, {
  Name = "~ادخـل كـود الاغنـية~",
  Default = "",
  PlaceholderText = "~ادخـل الاغنيـه سـيارة~",
  ClearText = true,
  Callback = function(Value)
local args1 = {
            [1] = "SkateBoard"
        }
        game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1NoMoto1rVehicle1s"):FireServer(unpack(args1))
 
        -- Replacing the static value with the input from the textbox
        local args2 = {
            [1] = "PickingScooterMusicText",
            [2] = Value -- Here, we use the textbox value to replace 35935204
        }
        game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1NoMoto1rVehicle1s"):FireServer(unpack(args2))
 
end 
})
 
 
local Paragraph = AddParagraph(Main, {" خصـائص السـياره"})
 
AddButton(Main, {
  Name = "  🔥نـار فـي سـياره ",
  Callback = function()
    local args = {
    [1] = "Fire"
}
 
game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1Player1sCa1r"):FireServer(unpack(args))
  end
})
AddButton(Main, {
  Name = "🪐دخـان فـي سـياره",
  Callback = function()
    local args = {
    [1] = "Smoke"
}
 
game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1Player1sCa1r"):FireServer(unpack(args))
  end
})
 
AddButton(Main, {
  Name = "تغييـر عجـلة السـيارة",
  Callback = function()
					local args = {
						[1] = "WheelNumber"
					}
					game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1Player1sCa1r"):FireServer(unpack(args))
 
end
})
 
 
AddButton(Main, {
  Name = "هـورن1",
  Callback = function()
					local args = {
						[1] = "Duke"
					}
					game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1Player1sCa1r"):FireServer(unpack(args))
 
end
})
 
 
 
 
AddButton(Main, {
  Name = "هـورن2",
  Callback = function()
					local args = {
						[1] = "Duke1"
					}
					game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1Player1sCa1r"):FireServer(unpack(args))
end
})
 
AddButton(Main, {
  Name = "تـغير لـون الـسـيارة",
  Callback = function()
					local args = {
						[1] = "PickingCarColor",
						[2] = Color3.new(math.random(), math.random(), math.random()) -- Random color
					}
 
					-- Fire the remote event
					game:GetService("ReplicatedStorage").RE:FindFirstChild("1Player1sCa1r"):FireServer(unpack(args))
 
end 
})
 
local Main = MakeTab({Name = "~الاعــب~"})
 
AddTextBox(Main, {
  Name = "ســـــرعـة | Speed",
  Default = "",
  PlaceholderText = "ادخل رقم",
  ClearText = true,
  Callback = function(value)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value     
 end
})
AddTextBox(Main, {
  Name = "قـــــفـز | Jump",
  Default = "",
  PlaceholderText = "ادخل رقم",
  ClearText = true,
  Callback = function(value)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = value    
  end
})
AddTextBox(Main, {
  Name = "Fov | شـاشـــه",
  Default = "",
  PlaceholderText = "ادخل رقم",
  ClearText = true,
  Callback = function(value)
local FovNumber = value
local Camera = workspace.CurrentCamera
Camera.FieldOfView = FovNumber  
  end
})
AddTextBox(Main, {
  Name = "Spin | دوران",
  Default = "",
  PlaceholderText = "ادخل رقم",
  ClearText = true,
  Callback = function(Value)
    getgenv().Spinspeed = Value
 
local Spin = Instance.new'BodyAngularVelocity'
Spin.Parent = game:GetService'Players'.LocalPlayer.Character:FindFirstChild'HumanoidRootPart'
Spin.MaxTorque = Vector3.new(0, math.huge, 100)
wait(0.1)
Spin.AngularVelocity = Vector3.new(100,Spinspeed,0)
  end
})
AddButton(Main, {
  Name = "اضـغط لاخـذ الـكنـبه ",
  Callback = function()
    local args={[1]="PickingTools",[2]="Couch"};game:GetService("ReplicatedStorage").RE:FindFirstChild("1Too1l"):InvokeServer(unpack(args))
  end
})
local infiniteJumpEnabled = false
 
-- Conectar o evento de pulo somente uma vez
local infiniteJumpConnection
 
-- Função de callback para o botão de alternância de pulo infinito
local function onInfiniteJumpToggle(value)
    infiniteJumpEnabled = value
    print("Infinite Jump Enabled:", infiniteJumpEnabled)
 
    -- Conectar o evento de pulo somente uma vez
    if not infiniteJumpConnection then
        infiniteJumpConnection = game:GetService("UserInputService").JumpRequest:Connect(function()
            if infiniteJumpEnabled then
                local player = game.Players.LocalPlayer
                local character = player.Character
                if character and character:FindFirstChildOfClass("Humanoid") then
                    character:FindFirstChildOfClass("Humanoid"):ChangeState("Jumping")
                end
            end
        end)
    end
end
 
-- Variáveis e funções para a visualização dos jogadores
local viewEnabled = false
local selectedViewPlayer = nil
local characterAddedConnection = nil
 
local function toggleView(enabled)
    if enabled then
        if selectedViewPlayer then
            local player = selectedViewPlayer
            if player then
                game.Workspace.CurrentCamera.CameraSubject = player.Character
                if characterAddedConnection then
                    characterAddedConnection:Disconnect()
                end
                characterAddedConnection = player.CharacterAdded:Connect(function(character)
                    game.Workspace.CurrentCamera.CameraSubject = character
                end)
                MakeNotifi({
                    Title = "Visualizando " .. player.Name,
                    Text = "Você está visualizando o jogador: " .. player.Name,
                    Time = 6
                })
            else
                print("Jogador não encontrado.")
                viewEnabled = false
            end
        else
            print("Nenhum jogador selecionado para a visualização.")
            viewEnabled = false
        end
    else
        if characterAddedConnection then
            characterAddedConnection:Disconnect()
            characterAddedConnection = nil
        end
        game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
    end
end
 
local value = "" -- Variável para armazenar o nome digitado
 
local function findPlayerByPartialNameOrNickname(partialName)
    value = partialName -- Atualiza a variável com o nome digitado completo
    for _, player in ipairs(game.Players:GetPlayers()) do
        if player.Name:lower():find(partialName:lower(), 1, true) or (player.DisplayName and player.DisplayName:lower():find(partialName:lower(), 1, true)) then
            return player
        end
    end
    return nil
end
 
-- Adicionando a caixa de texto para entrada do nome ou apelido do jogador
AddTextBox(Main, {
    Name = " اضـف يـوزر الاعـب",
    Default = "",
    PlaceholderText = "دخل اسم اللاعب",
    ClearText = true,
    Callback = function(value)
        if value == "" then
            MakeNotifi({
                Title = "‼️حصل خطأ‼️",
                Text = "Nome do jogador não foi digitado.",
                Time = 5
            })
            if viewEnabled then
                toggleView(false)
            end
            return
        end
 
        selectedViewPlayer = findPlayerByPartialNameOrNickname(value)
        if selectedViewPlayer then
            print("Jogador encontrado: " .. selectedViewPlayer.Name)
            if viewEnabled then
                toggleView(false)
                toggleView(true)
            end
        else
            MakeNotifi({
                Title = "Erro",
                Text = "Nenhum jogador encontrado com esse nome ou apelido.",
                Time = 7
            })
            if viewEnabled then
                toggleView(false)
            end
        end
    end
})
 
-- Adicionando o toggle para ativar/desativar a visualização
AddToggle(Main, {
    Name = "👀شــــاهـد",
    Default = false,
    Callback = function(enabled)
        viewEnabled = enabled
        toggleView(enabled)
    end
})
 
-- Conectando eventos de jogador removido
game.Players.PlayerRemoving:Connect(function(player)
    if selectedViewPlayer == player then
        selectedViewPlayer = nil
        if viewEnabled then
            toggleView(false)
            MakeNotifi({
                Title = "Jogador Saiu",
                Text = player.Name .. " saiu do jogo. Visualização desativada.",
                Time = 5
            })
        end
    end
end)
 
-- Função para manter a câmera no jogador selecionado
local function maintainView()
    while wait() do
        if viewEnabled and selectedViewPlayer then
            local player = selectedViewPlayer
            if player and game.Workspace.CurrentCamera.CameraSubject ~= player.Character then
                game.Workspace.CurrentCamera.CameraSubject = player.Character
            end
        end
    end
end
 
AddButton(Main, {
  Name = " 💫اعـادة دخـول الـى سـيرفـر",
  Callback = function()
    local ts = game:GetService("TeleportService")
				local p = game:GetService("Players").LocalPlayer
				ts:Teleport(game.PlaceId, p)
    print('Hello!')
  end
})
 
-- Adiciona o botão de alternância "Noclip"
local Toggle = AddToggle(Main, {
    Name = " اخـترق الـجـدار",
    Default = false,
    Callback = onNoclipToggle
})
