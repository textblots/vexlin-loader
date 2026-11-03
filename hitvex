local _a=game:GetService("Players")
local _b=game:GetService("UserInputService")
local _c=_a.LocalPlayer
local function _d()
    if gethui then
        local _v1,_v2=pcall(gethui)
        if _v1 and _v2 then return _v2 end
    end
    local _v3,_v4=pcall(function() return game:GetService("CoreGui") end)
    if _v3 and _v4 then return _v4 end
    return _c:WaitForChild("PlayerGui")
end
local _e=_d()
do
    local _v5=_e:FindFirstChild("HitVex")
    if _v5 then _v5:Destroy() end
end
local _g,_h=1.0,6.0
local _i={on=false,m=2.0}
local _j={}
local _k=Color3.fromRGB(14,14,16)
local _l=Color3.fromRGB(24,24,28)
local _m=Color3.fromRGB(44,44,52)
local _n=Color3.fromRGB(224,224,230)
local _o=Color3.fromRGB(120,120,132)
local _p=Color3.fromRGB(90,200,140)
local _q=Color3.fromRGB(48,48,56)
local _r=Color3.fromRGB(212,88,88)
local _s=Color3.fromRGB(8,8,10)
local function _t(_p1,_p2,_p3)
    local _v6=Instance.new(_p1)
    for _l1,_l2 in pairs(_p2) do _v6[_l1]=_l2 end
    if _p3 then _v6.Parent=_p3 end
    return _v6
end
local function _u(_p4)
    return _p4.UserInputType==Enum.UserInputType.MouseButton1 or _p4.UserInputType==Enum.UserInputType.Touch
end
local function _v(_p5)
    return _p5.UserInputType==Enum.UserInputType.MouseMovement or _p5.UserInputType==Enum.UserInputType.Touch
end
local _w=_t("ScreenGui",{Name="HitVex",ResetOnSpawn=false,IgnoreGuiInset=true,ZIndexBehavior=Enum.ZIndexBehavior.Sibling},_e)
local _x=_t("Frame",{Name="w",Size=UDim2.fromOffset(220,168),Position=UDim2.new(0,14,0.5,-84),BackgroundColor3=_k,BorderSizePixel=0,Active=true},_w)
_t("UICorner",{CornerRadius=UDim.new(0,8)},_x)
_t("UIStroke",{Color=_m,Thickness=1,ApplyStrokeMode=Enum.ApplyStrokeMode.Border},_x)
local _y=_t("Frame",{Name="tb",Size=UDim2.new(1,0,0,30),BackgroundTransparency=1},_x)
_t("TextLabel",{Size=UDim2.new(1,-70,1,0),Position=UDim2.fromOffset(12,0),BackgroundTransparency=1,Font=Enum.Font.Code,TextSize=12,TextColor3=_p,TextXAlignment=Enum.TextXAlignment.Left,Text="HitVex"},_y)
local function _z(_p6,_p7,_p8)
    local _v7=_t("TextButton",{Size=UDim2.fromOffset(20,20),Position=UDim2.new(1,_p7,0,5),BackgroundColor3=_l,AutoButtonColor=false,BorderSizePixel=0,Font=Enum.Font.Code,TextSize=13,TextColor3=_p8,Text=_p6},_y)
    _t("UICorner",{CornerRadius=UDim.new(0,4)},_v7)
    return _v7
end
local _A=_z("_",-50,_n)
local _B=_z("x",-26,_r)
_t("Frame",{Size=UDim2.new(1,-20,0,1),Position=UDim2.fromOffset(10,30),BackgroundColor3=_m,BorderSizePixel=0},_x)
local _C=_t("Frame",{Name="in",Size=UDim2.new(1,-20,0,122),Position=UDim2.fromOffset(10,38),BackgroundTransparency=1},_x)
local _D=_t("TextButton",{Size=UDim2.new(1,0,0,28),Position=UDim2.fromOffset(0,0),BackgroundColor3=_q,AutoButtonColor=false,BorderSizePixel=0,Font=Enum.Font.Code,TextSize=12,TextColor3=_n,Text="off"},_C)
_t("UICorner",{CornerRadius=UDim.new(0,5)},_D)
local _E=_t("TextLabel",{Size=UDim2.new(1,0,0,16),Position=UDim2.fromOffset(0,34),BackgroundTransparency=1,Font=Enum.Font.Code,TextSize=11,TextColor3=_p,TextXAlignment=Enum.TextXAlignment.Left,Text="2.0"},_C)
local _F=_t("Frame",{Size=UDim2.new(1,0,0,6),Position=UDim2.fromOffset(0,56),BackgroundColor3=_q,BorderSizePixel=0},_C)
_t("UICorner",{CornerRadius=UDim.new(1,0)},_F)
local _G=_t("Frame",{Size=UDim2.new(0,0,1,0),BackgroundColor3=_p,BorderSizePixel=0},_F)
_t("UICorner",{CornerRadius=UDim.new(1,0)},_G)
local _H=_t("Frame",{Size=UDim2.fromOffset(12,12),AnchorPoint=Vector2.new(0.5,0.5),Position=UDim2.new(0,0,0.5,0),BackgroundColor3=_n,BorderSizePixel=0,ZIndex=3},_F)
_t("UICorner",{CornerRadius=UDim.new(1,0)},_H)
local _I=_t("TextButton",{Size=UDim2.new(1,0,0,30),Position=UDim2.fromOffset(0,44),BackgroundTransparency=1,AutoButtonColor=false,Text="",ZIndex=4},_C)
local _J=_t("TextButton",{Size=UDim2.fromOffset(58,22),Position=UDim2.new(1,-58,0,82),BackgroundColor3=_l,AutoButtonColor=false,BorderSizePixel=0,Font=Enum.Font.Code,TextSize=11,TextColor3=_r,Text="rst"},_C)
_t("UICorner",{CornerRadius=UDim.new(0,4)},_J)
_t("TextLabel",{Size=UDim2.new(0,90,0,16),Position=UDim2.fromOffset(0,86),BackgroundTransparency=1,Font=Enum.Font.Code,TextSize=10,TextColor3=_o,TextXAlignment=Enum.TextXAlignment.Left,Text="[rshift]"},_C)
local function _K()
    local _v8=math.clamp((_i.m-_g)/(_h-_g),0,1)
    _G.Size=UDim2.new(_v8,0,1,0)
    _H.Position=UDim2.new(_v8,0,0.5,0)
    _E.Text=string.format("%.1f",_i.m)
end
local function _L()
    if _i.on then
        _D.Text="on"
        _D.BackgroundColor3=_p
        _D.TextColor3=_s
    else
        _D.Text="off"
        _D.BackgroundColor3=_q
        _D.TextColor3=_n
    end
end
local function _M(_p9)
    if not _p9 or not _p9.Parent then return end
    if not _p9:FindFirstChildOfClass("Humanoid") then return end
    for _, _l3 in ipairs(_p9:GetDescendants()) do
        if _l3:IsA("BasePart") then
            local _v9=_j[_l3]
            if not _v9 then
                _v9=_l3.Size
                _j[_l3]=_v9
            end
            local _v10=Vector3.new(_v9.X*_i.m,_v9.Y*_i.m,_v9.Z*_i.m)
            if _l3.Size~=_v10 then
                _l3.Size=_v10
            end
        end
    end
end
local function _N()
    for _l4,_l5 in pairs(_j) do
        if _l4 and _l4.Parent then
            _l4.Size=_l5
        end
    end
    table.clear(_j)
end
local function _O()
    for _l6 in pairs(_j) do
        if not _l6.Parent then
            _j[_l6]=nil
        end
    end
    for _, _l7 in ipairs(_a:GetPlayers()) do
        if _l7~=_c then
            local _v11=_l7.Character
            if _v11 then
                _M(_v11)
            end
        end
    end
end
local function _P()
    local _v12=_w.AbsoluteSize
    local _v13=_x.AbsoluteSize
    local _v14=_x.AbsolutePosition
    _x.Position=UDim2.fromOffset(math.clamp(_v14.X,0,math.max(0,_v12.X-_v13.X)),math.clamp(_v14.Y,0,math.max(0,_v12.Y-_v13.Y)))
end
task.spawn(function()
    while _w.Parent do
        if _i.on then
            pcall(_O)
        end
        task.wait(0.15)
    end
end)
_D.MouseButton1Click:Connect(function()
    _i.on=not _i.on
    _L()
    if _i.on then _O() else _N() end
end)
_J.MouseButton1Click:Connect(function()
    _i.on=false
    _L()
    _N()
end)
local _Q=false
local function _R(_p10)
    local _v15=math.clamp((_p10-_F.AbsolutePosition.X)/math.max(_F.AbsoluteSize.X,1),0,1)
    local _v16=_g+(_h-_g)*_v15
    _i.m=math.floor(_v16*10+0.5)/10
    _K()
    if _i.on then _O() end
end
_I.InputBegan:Connect(function(_p11)
    if _u(_p11) then
        _Q=true
        _R(_p11.Position.X)
    end
end)
_I.InputChanged:Connect(function(_p12)
    if _Q and _v(_p12) then
        _R(_p12.Position.X)
    end
end)
_I.InputEnded:Connect(function(_p13)
    if _u(_p13) then
        _Q=false
    end
end)
local _S=false
_y.InputBegan:Connect(function(_p14)
    if _u(_p14) then
        _S=true
    end
end)
_y.InputChanged:Connect(function(_p15)
    if _S and _v(_p15) then
        local _v17=_p15.Delta
        _x.Position=UDim2.new(_x.Position.X.Scale,_x.Position.X.Offset+_v17.X,_x.Position.Y.Scale,_x.Position.Y.Offset+_v17.Y)
    end
end)
_y.InputEnded:Connect(function(_p16)
    if _u(_p16) then
        _S=false
        _P()
    end
end)
local _T=false
_A.MouseButton1Click:Connect(function()
    _T=not _T
    _C.Visible=not _T
    _x.Size=_T and UDim2.fromOffset(220,38) or UDim2.fromOffset(220,168)
    _A.Text=_T and "+" or "_"
end)
_B.MouseButton1Click:Connect(function()
    if _i.on then _N() end
    _w:Destroy()
end)
_w.Destroying:Connect(function()
    if next(_j) then _N() end
end)
_b.InputBegan:Connect(function(_p17,_p18)
    if _p18 then return end
    if _p17.KeyCode==Enum.KeyCode.RightShift then
        _i.on=not _i.on
        _L()
        if _i.on then _O() else _N() end
    end
end)
_K()
_L()
