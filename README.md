 if game:GetService("\67\111\114\101\71\117\105"):FindFirstChild("\68\105\110\111\85\73") then game:GetService("\67\111\114\101\71\117\105"):FindFirstChild("\68\105\110\111\85\73"):Destroy() end if game.CoreGui:FindFirstChild("\83\79\77\69\88\72\85\66\77\79\68\73\76\69") then game.CoreGui:FindFirstChild("\83\79\77\69\88\72\85\66\77\79\68\73\76\69"):Destroy() end spawn(function() while wait() do pcall(function() game.CoreGui.RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(b) if b.Name == "\69\114\114\111\114\80\114\111\109\112\116" then  game:GetService("\84\101\108\101\112\111\114\116\83\101\114\118\105\99\101"):TeleportToPlaceInstance(game.PlaceId, game.JobId, game:GetService("\80\108\97\121\101\114\115").LocalPlayer)     end end) end) end end) local o = game:GetService("\86\105\114\116\117\97\108\85\115\101\114") game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Idled:connect(function() o:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame) wait(1) o:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame) end) local q = Instance.new("\83\99\114\101\101\110\71\117\105") local e = Instance.new("\84\101\120\116\66\117\116\116\111\110") local r = Instance.new("\85\73\67\111\114\110\101\114") local l = Instance.new("\73\109\97\103\101\76\97\98\101\108") q.Name = "\83\79\77\69\88\72\85\66\77\79\68\73\76\69" q.Parent = game.CoreGui q.ZIndexBehavior = Enum.ZIndexBehavior.Sibling e.Name = "\77\79\68\73\76\69\71\85\73\83\79\77\69\88\72\85\66" e.Parent = q e.BackgroundColor3 = Color3.fromRGB(30,20,20) e.BackgroundTransparency = 0.1 e.BorderSizePixel = 0 e.Position = UDim2.new(0.120833337, 0, 0.0952890813, 0) e.Size = UDim2.new(0, 50, 0, 50) e.Font = Enum.Font.SourceSans e.Text = "" e.TextColor3 = Color3.fromRGB(0, 0, 0) e.TextSize = 14.000 e.Draggable = true e.MouseButton1Click:Connect(function() game.CoreGui:FindFirstChild("\68\105\110\111\85\73").Enabled = not game.CoreGui:FindFirstChild("\68\105\110\111\85\73").Enabled end) do if game:GetService("\67\111\114\101\71\117\105"):FindFirstChild("\68\105\110\111\85\73") then end end r.Name = "\77\79\68\73\76\69\71\85\73\83\79\77\69\88\72\85\66\72\85\73" r.Parent = e l.Name = "\77\79\68\73\76\69\77\65\71\69" l.Parent = e l.BackgroundColor3 = Color3.fromRGB(255, 255, 255) l.BackgroundTransparency = 1.000 l.BorderSizePixel = 0 l.Position = UDim2.new(0.234619886, 0, 0.239034846, 0) l.Size = UDim2.new(0, 25, 0, 25) l.Image = "\104\116\116\112\58\47\47\119\119\119\46\114\111\98\108\111\120\46\99\111\109\47\97\115\115\101\116\47\63\105\100\61\54\48\51\49\48\55\53\57\51\56" wait(1) local t = game:GetService("\84\119\101\101\110\83\101\114\118\105\99\101") local _ = game:GetService("\85\115\101\114\73\110\112\117\116\83\101\114\118\105\99\101") local a_ = {} function a_:CreateWindow(dinotitle) local n = Instance.new("\83\99\114\101\101\110\71\117\105") local sn = Instance.new("\70\114\97\109\101") local fs = Instance.new("\84\101\120\116\76\97\98\101\108") local gf = Instance.new("\84\101\120\116\76\97\98\101\108") local ig = Instance.new("\84\101\120\116\76\97\98\101\108") local bi = Instance.new("\83\99\114\111\108\108\105\110\103\70\114\97\109\101") local d = Instance.new("\85\73\76\105\115\116\76\97\121\111\117\116") local p = Instance.new("\70\114\97\109\101") n.Name = "\68\105\110\111\85\73" n.Parent = game.CoreGui n.ZIndexBehavior = Enum.ZIndexBehavior.Sibling sn.Name = "\87\105\110\100\111\119" sn.Parent = n sn.BackgroundColor3 = Color3.fromRGB(40, 40, 40) sn.BorderSizePixel = 0 sn.Position = UDim2.new(0, 392, 0, 264) sn.Size = UDim2.new(0, 390, 0, 350) fs.Name = "\68\105\110\111\72\117\98\84\101\120\116\49" fs.Parent = sn fs.BackgroundColor3 = Color3.fromRGB(255, 255, 255) fs.BackgroundTransparency = 1.000 fs.BorderSizePixel = 0 fs.Position = UDim2.new(0, 5, 0, 0) fs.Size = UDim2.new(0, 35, 0, 20) fs.Font = Enum.Font.GothamSemibold fs.Text = "\85\112\114\105\103\104\116" fs.TextColor3 = Color3.fromRGB(180, 180, 180) fs.TextSize = 13.000 gf.Name = "\68\105\110\111\72\117\98\84\101\120\116\50" gf.Parent = sn gf.BackgroundColor3 = Color3.fromRGB(255, 255, 255) gf.BackgroundTransparency = 1.000 gf.BorderSizePixel = 0 gf.Position = UDim2.new(0, 40, 0, 0) gf.Size = UDim2.new(0, 35, 0, 20) gf.Font = Enum.Font.GothamSemibold gf.Text = "\32\32\32\32\72\85\66\32\124" gf.TextColor3 = Color3.fromRGB(55, 122, 204) gf.TextSize = 13.000 ig.Name = "\87\105\110\100\111\119\84\101\120\116" ig.Parent = sn ig.BackgroundColor3 = Color3.fromRGB(255, 255, 255) ig.BackgroundTransparency = 1.000 ig.BorderSizePixel = 0 ig.Position = UDim2.new(0, 85, 0, 0) ig.Size = UDim2.new(0, 305, 0, 20) ig.Font = Enum.Font.GothamSemibold ig.Text = dinotitle or "\71\97\109\101\32\84\105\116\108\101" ig.TextColor3 = Color3.fromRGB(150, 150, 150) ig.TextSize = 13.000 ig.TextXAlignment = Enum.TextXAlignment.Left bi.Name = "\84\97\98\87\105\110\100\111\119" bi.Parent = sn bi.Active = true bi.BackgroundColor3 = Color3.fromRGB(30, 30, 30) bi.BorderSizePixel = 0 bi.Position = UDim2.new(0, 7, 0, 20) bi.Size = UDim2.new(0, 375, 0, 20) bi.CanvasSize = UDim2.new(2, 0, 0, 0) bi.ScrollBarThickness = 2 d.Name = "\84\97\98\87\105\110\100\111\119\76\105\115\116" d.Parent = bi d.FillDirection = Enum.FillDirection.Horizontal d.SortOrder = Enum.SortOrder.LayoutOrder p.Name = "\67\111\110\116\97\105\110\101\114\72\111\108\100\101\114" p.Parent = sn p.BackgroundColor3 = Color3.fromRGB(40, 40, 40) p.BorderSizePixel = 0 p.Position = UDim2.new(0, 0, 0, 40) p.Size = UDim2.new(0, 390, 0, 310) bi.CanvasSize = UDim2.new(0, 0 + d.AbsoluteContentSize.X, 0, 0) d:GetPropertyChangedSignal("\65\98\115\111\108\117\116\101\67\111\110\116\101\110\116\83\105\122\101"):Connect(function() bi.CanvasSize = UDim2.new(0, 0 + d.AbsoluteContentSize.X, 0, 0) end) local hp = sn local ch local jc local mj local om local function a(h) local qo = h.Position - mj hp.Position = UDim2.new(om.X.Scale, om.X.Offset + qo.X, om.Y.Scale, om.Y.Offset + qo.Y) end hp.InputBegan:Connect(function(h) if h.UserInputType == Enum.UserInputType.MouseButton1 or h.UserInputType == Enum.UserInputType.Touch then ch = true mj = h.Position om = hp.Position h.Changed:Connect(function() if h.UserInputState == Enum.UserInputState.End then ch = false end end) end end) hp.InputChanged:Connect(function(h) if h.UserInputType == Enum.UserInputType.MouseMovement or h.UserInputType == Enum.UserInputType.Touch then jc = h end end) _.InputChanged:Connect(function(h) if h == jc and ch then a(h) end end) local lreqo = {} function lreqo:NewPage(pagetitle) local re = Instance.new("\83\99\114\111\108\108\105\110\103\70\114\97\109\101") local lr = Instance.new("\85\73\76\105\115\116\76\97\121\111\117\116") re.Name = pagetitle or "\67\111\110\116\97\105\110\101\114" re.Parent = p re.Active = true re.BackgroundColor3 = Color3.fromRGB(40, 40, 40) re.BorderSizePixel = 0 re.Position = UDim2.new(0, 5, 0, 5) re.Size = UDim2.new(0, 380, 0, 300) re.Visible = false re.CanvasSize = UDim2.new(0, 0, 0, 5 + lr.Padding.Offset + lr.AbsoluteContentSize.Y) re.ScrollBarThickness = 2 lr.Name = "\67\111\110\116\97\105\110\101\114\76\105\115\116" lr.Parent = re lr.HorizontalAlignment = Enum.HorizontalAlignment.Center lr.SortOrder = Enum.SortOrder.LayoutOrder lr.Padding = UDim.new(0, 5) lr:GetPropertyChangedSignal("\65\98\115\111\108\117\116\101\67\111\110\116\101\110\116\83\105\122\101"):Connect(function() re.CanvasSize = UDim2.new(0, 0, 0, 0 + lr.Padding.Offset + lr.AbsoluteContentSize.Y) end) re.ChildAdded:Connect(function() re.CanvasSize = UDim2.new(0, 0, 0, 0 + lr.Padding.Offset + lr.AbsoluteContentSize.Y) end) local tl = Instance.new("\84\101\120\116\66\117\116\116\111\110") tl.Name = "\84\97\98\66\117\116\116\111\110" tl.Parent = bi tl.BackgroundColor3 = Color3.fromRGB(255, 255, 255) tl.BackgroundTransparency = 1.000 tl.BorderSizePixel = 0 tl.Position = UDim2.new(0, 5, 0, 0) tl.Size = UDim2.new(0, 100, 0, 20) tl.Font = Enum.Font.GothamSemibold tl.Text = pagetitle or "\84\97\98" tl.TextColor3 = Color3.fromRGB(180, 180, 180) tl.TextSize = 13.000 tl.Size = UDim2.new(0, 10 + tl.TextBounds.X, 0, 20) tl.MouseButton1Click:Connect(function() for _, co in pairs(p:GetChildren()) do if co:IsA("\83\99\114\111\108\108\105\110\103\70\114\97\109\101") then co.Visible = false end end for _, tb in pairs(bi:GetChildren()) do if tb:IsA("\84\101\120\116\66\117\116\116\111\110") then t:Create(tb, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {TextColor3 = Color3.fromRGB(180, 180, 180)}):Play() end end t:Create(tl, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {TextColor3 = Color3.fromRGB(125, 125, 125)}):Play() re.Visible = true end) local tlreq = {} function tlreq:NewSection(sectiontitle) local a_t = Instance.new("\70\114\97\109\101") local na = Instance.new("\84\101\120\116\76\97\98\101\108") local sna = Instance.new("\70\114\97\109\101") local fsn = Instance.new("\85\73\67\111\114\110\101\114") local gfs = Instance.new("\85\73\76\105\115\116\76\97\121\111\117\116") a_t.Name = sectiontitle or "\83\101\99\116\105\111\110" a_t.Parent = re a_t.BackgroundColor3 = Color3.fromRGB(40, 40, 40) a_t.Position = UDim2.new(0.0263157897, 0, 0, 0) a_t.Size = UDim2.new(0, 360, 0, 20) na.Name = "\83\101\99\116\105\111\110\84\105\116\108\101" na.Parent = a_t na.BackgroundColor3 = Color3.fromRGB(255, 255, 255) na.BackgroundTransparency = 1.000 na.BorderSizePixel = 0 na.Size = UDim2.new(0, 360, 0, 15) na.Font = Enum.Font.GothamSemibold na.Text = sectiontitle or "\83\101\99\116\105\111\110" na.TextColor3 = Color3.fromRGB(180, 180, 180) na.TextSize = 13.000 sna.Name = "\83\101\99\116\105\111\110\73\110" sna.Parent = a_t sna.BackgroundColor3 = Color3.fromRGB(40, 40, 40) sna.BorderSizePixel = 0 sna.Position = UDim2.new(0, 0, 0, 20) sna.Size = UDim2.new(0, 360, 0, 70) fsn.CornerRadius = UDim.new(0, 2) fsn.Name = "\83\101\99\116\105\111\110\73\110\85\73\67\111\114\110\101\114" fsn.Parent = sna gfs.Name = "\83\101\99\116\105\111\110\73\110\76\105\115\116" gfs.Parent = sna gfs.HorizontalAlignment = Enum.HorizontalAlignment.Center gfs.SortOrder = Enum.SortOrder.LayoutOrder gfs.Padding = UDim.new(0, 10) sna.Size = UDim2.new(0, 360, 0, 5 + gfs.AbsoluteContentSize.Y + gfs.Padding.Offset) gfs:GetPropertyChangedSignal("\65\98\115\111\108\117\116\101\67\111\110\116\101\110\116\83\105\122\101"):Connect(function() sna.Size = UDim2.new(0, 360, 0, 5 + gfs.AbsoluteContentSize.Y + gfs.Padding.Offset) end) local function s() local igf = 0 igf = gfs.AbsoluteContentSize.Y re.CanvasSize = UDim2.new(0, 0, 0, igf + 35 + gfs.Padding.Offset) end local function f() a_t.Size = UDim2.new(0, 360, 0, 20 + gfs.AbsoluteContentSize.Y + gfs.Padding.Offset) end s() f() gfs:GetPropertyChangedSignal("\65\98\115\111\108\117\116\101\67\111\110\116\101\110\116\83\105\122\101"):Connect(function() s() f() end) local big = {} function big:CreateButton(buttontitle, buttoncallback) local db = Instance.new("\84\101\120\116\66\117\116\116\111\110") local pd = Instance.new("\85\73\67\111\114\110\101\114") local hpd = Instance.new("\85\73\83\116\114\111\107\101") local chp = Instance.new("\73\109\97\103\101\76\97\98\101\108") db.Name = buttontitle or "\66\117\116\116\111\110\72\111\108\100\101\114" db.Parent = sna db.BackgroundColor3 = Color3.fromRGB(39, 86, 144) db.BorderSizePixel = 0 db.Position = UDim2.new(0, 5, 0, 0) db.Size = UDim2.new(0, 350, 0, 25) db.AutoButtonColor = false db.Font = Enum.Font.GothamSemibold db.Text = buttontitle or "\66\117\116\116\111\110\32\124\32\67\108\105\99\107\32\77\101" db.TextColor3 = Color3.fromRGB(180, 180, 180) db.TextSize = 13.000 pd.CornerRadius = UDim.new(0, 4) pd.Name = "\66\117\116\116\111\110\72\111\108\100\101\114\85\73\67\111\114\110\101\114" pd.Parent = db hpd.Name = "\66\117\116\116\111\110\72\111\108\100\101\114\85\73\83\116\114\111\107\101" hpd.Parent = db hpd.ApplyStrokeMode = Enum.ApplyStrokeMode.Border hpd.Color = Color3.fromRGB(35, 78, 130) hpd.LineJoinMode = Enum.LineJoinMode.Round hpd.Thickness = 1.6 hpd.Transparency = 0 hpd.Enabled = true hpd.Archivable = true chp.Name = "\66\117\116\116\111\110\73\109\97\103\101" chp.Parent = db chp.BackgroundColor3 = Color3.fromRGB(255, 255, 255) chp.BackgroundTransparency = 1.000 chp.BorderSizePixel = 0 chp.Position = UDim2.new(0, 5, 0, 3) chp.Size = UDim2.new(0, 18, 0, 18) chp.Image = "\114\98\120\97\115\115\101\116\105\100\58\47\47\55\56\51\57\53\48\53\56\48\57" chp.ImageColor3 = Color3.fromRGB(180, 180, 180) db.MouseEnter:Connect(function() t:Create(db, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {TextColor3 = Color3.fromRGB(125, 125, 125)}):Play() t:Create(chp, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {ImageColor3 = Color3.fromRGB(125, 125, 125)}):Play() end) db.MouseLeave:Connect(function() t:Create(db, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {TextColor3 = Color3.fromRGB(180, 180, 180)}):Play() t:Create(chp, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {ImageColor3 = Color3.fromRGB(180, 180, 180)}):Play() t:Create(db, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Size = UDim2.new(0, 350, 0, 25)}):Play() end) db.MouseButton1Down:Connect(function() t:Create(db, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Size = UDim2.new(0, 345, 0, 23)}):Play() end) db.MouseButton1Up:Connect(function() t:Create(db, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Size = UDim2.new(0, 350, 0, 25)}):Play() end) db.MouseButton1Click:Connect(function() pcall(function() buttoncallback() end) end) end function big:CreateToggle(toggletitle, togglecallback) local jch = Instance.new("\70\114\97\109\101") local mjc = Instance.new("\85\73\67\111\114\110\101\114") local omj = Instance.new("\73\109\97\103\101\76\97\98\101\108") local qom = Instance.new("\84\101\120\116\76\97\98\101\108") local eqo = Instance.new("\73\109\97\103\101\76\97\98\101\108") local req = Instance.new("\85\73\67\111\114\110\101\114") local lre = Instance.new("\73\109\97\103\101\76\97\98\101\108") local tlr = Instance.new("\85\73\67\111\114\110\101\114") local _tl = Instance.new("\84\101\120\116\66\117\116\116\111\110") local a_tl = Instance.new("\85\73\83\116\114\111\107\101") jch.Name = toggletitle or "\84\111\103\103\108\101\72\111\108\100\101\114" jch.Parent = sna jch.BackgroundColor3 = Color3.fromRGB(40, 40, 40) jch.BorderSizePixel = 0 jch.Size = UDim2.new(0, 350, 0, 25) mjc.CornerRadius = UDim.new(0, 1) mjc.Name = "\84\111\103\103\108\101\72\111\108\100\101\114\85\73\67\111\114\110\101\114" mjc.Parent = jch omj.Name = "\84\111\103\103\108\101\73\109\97\103\101" omj.Parent = jch omj.BackgroundColor3 = Color3.fromRGB(255, 255, 255) omj.BackgroundTransparency = 1.000 omj.BorderSizePixel = 0 omj.Position = UDim2.new(0, 5, 0, 3) omj.Size = UDim2.new(0, 18, 0, 18) omj.Image = "\114\98\120\97\115\115\101\116\105\100\58\47\47\55\56\51\50\48\56\51\55\52\52" omj.ImageColor3 = Color3.fromRGB(200, 200, 200) qom.Name = "\84\111\103\103\108\101\84\105\116\108\101" qom.Parent = jch qom.BackgroundColor3 = Color3.fromRGB(255, 255, 255) qom.BackgroundTransparency = 1.000 qom.BorderSizePixel = 0 qom.Position = UDim2.new(0, 25, 0, 0) qom.Size = UDim2.new(0, 250, 0, 25) qom.Font = Enum.Font.GothamSemibold qom.Text = toggletitle or "\84\111\103\103\108\101\32\124\32\84\111\103\103\108\101\32\77\101\32\33" qom.TextColor3 = Color3.fromRGB(180, 180, 180) qom.TextSize = 13.000 qom.TextXAlignment = Enum.TextXAlignment.Left eqo.Name = "\84\111\103\103\108\101\79\117\116" eqo.Parent = jch eqo.BackgroundColor3 = Color3.fromRGB(25, 25, 25) eqo.Position = UDim2.new(0, 310, 0, 4) eqo.Size = UDim2.new(0, 34, 0, 16) eqo.Image = "\114\98\120\97\115\115\101\116\58\47\47\116\101\120\116\117\114\101\115\47\117\105\47\71\117\105\73\109\97\103\101\80\108\97\99\101\104\111\108\100\101\114\46\112\110\103" eqo.ImageTransparency = 1.000 req.CornerRadius = UDim.new(0, 1000) req.Name = "\84\111\103\103\108\101\79\117\116\85\73\67\111\114\110\101\114" req.Parent = eqo lre.Name = "\84\111\103\103\108\101\73\110" lre.Parent = eqo lre.BackgroundColor3 = Color3.fromRGB(39, 86, 144) lre.Position = UDim2.new(0, 2, 0, 2) lre.Size = UDim2.new(0, 12, 0, 12) lre.Image = "\114\98\120\97\115\115\101\116\58\47\47\116\101\120\116\117\114\101\115\47\117\105\47\71\117\105\73\109\97\103\101\80\108\97\99\101\104\111\108\100\101\114\46\112\110\103" lre.ImageTransparency = 1.000 tlr.CornerRadius = UDim.new(0, 1000) tlr.Name = "\84\111\103\103\108\101\73\110\85\73\67\111\114\110\101\114" tlr.Parent = lre _tl.Name = "\84\111\103\103\108\101\72\111\108\100\101\114\66\117\116\116\111\110" _tl.Parent = jch _tl.BackgroundColor3 = Color3.fromRGB(255, 255, 255) _tl.BackgroundTransparency = 1.000 _tl.BorderSizePixel = 0 _tl.Size = UDim2.new(0, 350, 0, 25) _tl.ZIndex = 2 _tl.Font = Enum.Font.SourceSans _tl.Text = "" _tl.TextColor3 = Color3.fromRGB(0, 0, 0) _tl.TextSize = 14.000 a_tl.Name = "\84\111\103\103\108\101\72\111\108\100\101\114\85\73\83\116\114\111\107\101" a_tl.Parent = jch a_tl.ApplyStrokeMode = Enum.ApplyStrokeMode.Border a_tl.Color = Color3.fromRGB(35, 78, 130) a_tl.LineJoinMode = Enum.LineJoinMode.Round a_tl.Thickness = 1.6 a_tl.Transparency = 0 a_tl.Enabled = true a_tl.Archivable = true local na_ = false _tl.MouseEnter:Connect(function() t:Create(qom, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {TextColor3 = Color3.fromRGB(125, 125, 125)}):Play() t:Create(omj, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {ImageColor3 = Color3.fromRGB(125, 125, 125)}):Play() end) _tl.MouseLeave:Connect(function() t:Create(qom, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {TextColor3 = Color3.fromRGB(180, 180, 180)}):Play() t:Create(omj, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {ImageColor3 = Color3.fromRGB(180, 180, 180)}):Play() t:Create(jch, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Size = UDim2.new(0, 350, 0, 25)}):Play() end) _tl.MouseButton1Down:Connect(function() t:Create(jch, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Size = UDim2.new(0, 345, 0, 23)}):Play() end) _tl.MouseButton1Up:Connect(function() t:Create(jch, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Size = UDim2.new(0, 350, 0, 25)}):Play() end) _tl.MouseButton1Click:Connect(function() if na_ then t:Create(lre, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = UDim2.new(0, 2, 0, 2)}):Play() na_ = false pcall(function() togglecallback(na_) end) else t:Create(lre, TweenInfo.new(0.12, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), {Position = UDim2.new(0, 20, 0, 2)}):Play() na_ = true pcall(function() togglecallback(na_) end) end end) end function big:CreateSlider(slidertitle, minvalue, maxvalue, callback) local sna_ = Instance.new("\70\114\97\109\101") local fsna = Instance.new("\85\73\67\111\114\110\101\114") local gfsn = Instance.new("\73\109\97\103\101\76\97\98\101\108") local igfs = Instance.new("\84\101\120\116\76\97\98\101\108") local bigf = Instance.new("\73\109\97\103\101\66\117\116\116\111\110") local dbi = Instance.new("\85\73\67\111\114\110\101\114") local pdb = Instance.new("\73\109\97\103\101\76\97\98\101\108") local hpdb = Instance.new("\85\73\67\111\114\110\101\114") local chpd = Instance.new("\84\101\120\116\76\97\98\101\108") local jchp = Instance.new("\85\73\83\116\114\111\107\101") sna_.Name = slidertitle or "\83\108\105\100\101\114\72\111\108\100\101\114" sna_.Parent = sna sna_.BackgroundColor3 = Color3.fromRGB(40, 40, 40) sna_.BorderSizePixel = 0 sna_.Position = UDim2.new(0, 5, 0, 60) sna_.Size = UDim2.new(0, 350, 0, 40) fsna.CornerRadius = UDim.new(0, 1) fsna.Name = "\83\108\105\100\101\114\72\111\108\100\101\114\85\73\67\111\114\110\101\114" fsna.Parent = sna_ gfsn.Name = "\83\108\105\100\101\114\73\109\97\103\101" gfsn.Parent = sna_ gfsn.BackgroundColor3 = Color3.fromRGB(255, 255, 255) gfsn.BackgroundTransparency = 1.000 gfsn.BorderSizePixel = 0 gfsn.Position = UDim2.new(0, 5, 0, 3) gfsn.Size = UDim2.new(0, 18, 0, 18) gfsn.Image = "\114\98\120\97\115\115\101\116\105\100\58\47\47\55\56\51\57\55\50\50\51\54\57" gfsn.ImageColor3 = Color3.fromRGB(200, 200, 200) igfs.Name = "\83\108\105\100\101\114\72\111\108\100\101\114\84\105\116\108\101" igfs.Parent = sna_ igfs.BackgroundColor3 = Color3.fromRGB(255, 255, 255) igfs.BackgroundTransparency = 1.000 igfs.BorderSizePixel = 0 igfs.Position = UDim2.new(0, 25, 0, 0) igfs.Size = UDim2.new(0, 250, 0, 25) igfs.Font = Enum.Font.GothamSemibold igfs.Text = slidertitle or "\83\108\105\100\101\114\32\124\32\72\111\108\100\32\77\101\32\33" igfs.TextColor3 = Color3.fromRGB(180, 180, 180) igfs.TextSize = 13.000 igfs.TextXAlignment = Enum.TextXAlignment.Left bigf.Name = "\83\108\105\100\101\114\66\117\116\116\111\110" bigf.Parent = sna_ bigf.BackgroundColor3 = Color3.fromRGB(25, 25, 25) bigf.Position = UDim2.new(0, 10, 0, 25) bigf.Size = UDim2.new(0, 300, 0, 7) bigf.AutoButtonColor = false bigf.Image = "\114\98\120\97\115\115\101\116\58\47\47\116\101\120\116\117\114\101\115\47\117\105\47\71\117\105\73\109\97\103\101\80\108\97\99\101\104\111\108\100\101\114\46\112\110\103" bigf.ImageTransparency = 1.000 dbi.CornerRadius = UDim.new(0, 1000) dbi.Name = "\83\108\105\100\101\114\66\117\116\116\111\110\85\73\67\111\114\110\101\114" dbi.Parent = bigf pdb.Name = "\83\108\105\100\101\114\73\110" pdb.Parent = bigf pdb.BackgroundColor3 = Color3.fromRGB(39, 86, 144) pdb.Size = UDim2.new(0, 0, 0, 7) pdb.Image = "\114\98\120\97\115\115\101\116\58\47\47\116\101\120\116\117\114\101\115\47\117\105\47\71\117\105\73\109\97\103\101\80\108\97\99\101\104\111\108\100\101\114\46\112\110\103" pdb.ImageTransparency = 1.000 hpdb.CornerRadius = UDim.new(0, 1000) hpdb.Name = "\83\108\105\100\101\114\73\110\85\73\67\111\114\110\101\114" hpdb.Parent = pdb chpd.Name = "\86\97\108" chpd.Parent = sna_ chpd.BackgroundColor3 = Color3.fromRGB(255, 255, 255) chpd.BackgroundTransparency = 1.000 chpd.BorderSizePixel = 0 chpd.Position = UDim2.new(0, 282, 0, 0) chpd.Size = UDim2.new(0, 60, 0, 25) chpd.Font = Enum.Font.GothamSemibold chpd.Text = minvalue or "\48" chpd.TextColor3 = Color3.fromRGB(150, 150, 150) chpd.TextSize = 13.000 chpd.TextXAlignment = Enum.TextXAlignment.Right jchp.Name = "\83\108\105\100\101\114\72\111\108\100\101\114\85\73\83\116\114\111\107\101" jchp.Parent = sna_ jchp.ApplyStrokeMode = Enum.ApplyStrokeMode.Border jchp.Color = Color3.fromRGB(35, 78, 130) jchp.LineJoinMode = Enum.LineJoinMode.Round jchp.Thickness = 1.6 jchp.Transparency = 0 jchp.Enabled = true jchp.Archivable = true minvalue = minvalue or 0 maxvalue = maxvalue or 100 callback = callback or function() end local mjch = game.Players.LocalPlayer:GetMouse() local omjc = game:GetService("\85\115\101\114\73\110\112\117\116\83\101\114\118\105\99\101") local qomj; bigf.MouseButton1Down:Connect(function() qomj = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / 300) * pdb.AbsoluteSize.X) + tonumber(minvalue)) or 0 pcall(function() callback(qomj) end) pdb.Size = UDim2.new(0, math.clamp(mjch.X - pdb.AbsolutePosition.X, 0, 300), 0, 7) moveconnection = mjch.Move:Connect(function() chpd.Text = qomj qomj = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / 300) * pdb.AbsoluteSize.X) + tonumber(minvalue)) pcall(function() callback(qomj) end) pdb.Size = UDim2.new(0, math.clamp(mjch.X - pdb.AbsolutePosition.X, 0, 300), 0, 7) end) releaseconnection = omjc.InputEnded:Connect(function(c) if c.UserInputType == Enum.UserInputType.MouseButton1 then qomj = math.floor((((tonumber(maxvalue) - tonumber(minvalue)) / 300) * pdb.AbsoluteSize.X) + tonumber(minvalue)) pcall(function() callback(qomj) end) pdb.Size = UDim2.new(0, math.clamp(mjch.X - pdb.AbsolutePosition.X, 0, 300), 0, 7) moveconnection:Disconnect() releaseconnection:Disconnect() end end) end) end function big:CreateTextBox(textboxtitle, textboxplaceholdertitle,textboxcallback) local eqom = Instance.new("\70\114\97\109\101") local reqo = Instance.new("\85\73\67\111\114\110\101\114") local lreq = Instance.new("\73\109\97\103\101\76\97\98\101\108") local tlre = Instance.new("\84\101\120\116\76\97\98\101\108") local _tlr = Instance.new("\84\101\120\116\66\111\120") local a_tlr = Instance.new("\85\73\83\116\114\111\107\101") eqom.Name = textboxtitle or "\84\101\120\116\66\111\120\84\111\103\103\108\101" eqom.Parent = sna eqom.BackgroundColor3 = Color3.fromRGB(40, 40, 40) eqom.BorderSizePixel = 0 eqom.Size = UDim2.new(0, 350, 0, 25) reqo.CornerRadius = UDim.new(0, 1) reqo.Name = "\84\101\120\116\66\111\120\84\111\103\103\108\101\85\73\67\111\114\110\101\114" reqo.Parent = eqom lreq.Name = "\84\101\120\116\66\111\120\73\109\97\103\101" lreq.Parent = eqom lreq.BackgroundColor3 = Color3.fromRGB(255, 255, 255) lreq.BackgroundTransparency = 1.000 lreq.BorderSizePixel = 0 lreq.Position = UDim2.new(0, 5, 0, 3) lreq.Size = UDim2.new(0, 18, 0, 18) lreq.Image = "\114\98\120\97\115\115\101\116\105\100\58\47\47\55\56\51\50\48\53\48\52\57\52" lreq.ImageColor3 = Color3.fromRGB(200, 200, 200) tlre.Name = "\84\101\120\116\66\111\120\84\105\116\108\101" tlre.Parent = eqom tlre.BackgroundColor3 = Color3.fromRGB(255, 255, 255) tlre.BackgroundTransparency = 1.000 tlre.BorderSizePixel = 0 tlre.Position = UDim2.new(0, 25, 0, 0) tlre.Size = UDim2.new(0, 175, 0, 25) tlre.Font = Enum.Font.GothamSemibold tlre.Text = textboxtitle or "\84\101\120\116\66\111\120" tlre.TextColor3 = Color3.fromRGB(180, 180, 180) tlre.TextSize = 13.000 tlre.TextXAlignment = Enum.TextXAlignment.Left _tlr.Parent = eqom _tlr.BackgroundColor3 = Color3.fromRGB(25, 25, 25) _tlr.BorderSizePixel = 0 _tlr.Position = UDim2.new(0, 210, 0, 4) _tlr.Size = UDim2.new(0, 135, 0, 18) _tlr.Font = Enum.Font.GothamSemibold _tlr.PlaceholderText = textboxplaceholdertitle or "\69\110\116\101\114\32\84\101\120\116" _tlr.Text = "" _tlr.TextColor3 = Color3.fromRGB(200, 200, 200) _tlr.TextSize = 12.000 a_tlr.Name = "\84\101\120\116\66\111\120\72\111\108\100\101\114\85\73\83\116\114\111\107\101" a_tlr.Parent = eqom a_tlr.ApplyStrokeMode = Enum.ApplyStrokeMode.Border a_tlr.Color = Color3.fromRGB(35, 78, 130) a_tlr.LineJoinMode = Enum.LineJoinMode.Round a_tlr.Thickness = 1.6 a_tlr.Transparency = 0 a_tlr.Enabled = true a_tlr.Archivable = true _tlr.FocusLost:Connect(function() pcall(function() textboxcallback(_tlr.Text) end) end) end function big:CreateDropdown(dropdowntitle, list, dropdowncallback) list = list or {} local na_t = Instance.new("\70\114\97\109\101") local sna_t = Instance.new("\85\73\67\111\114\110\101\114") local fsna_ = Instance.new("\73\109\97\103\101\76\97\98\101\108") local omjch = Instance.new("\84\101\120\116\76\97\98\101\108") local igfsn = Instance.new("\84\101\120\116\66\117\116\116\111\110") local bigfs = Instance.new("\70\114\97\109\101") local dbig = Instance.new("\85\73\76\105\115\116\76\97\121\111\117\116") local pdbi = Instance.new("\84\101\120\116\76\97\98\101\108") local hpdbi = Instance.new("\85\73\83\116\114\111\107\101") na_t.Name = dropdowntitle or "\68\114\111\112\100\111\119\110\72\111\108\100\101\114" na_t.Parent = sna na_t.BackgroundColor3 = Color3.fromRGB(40, 40, 40) na_t.BorderSizePixel = 0 na_t.ClipsDescendants = true na_t.Size = UDim2.new(0, 350, 0, 25) sna_t.CornerRadius = UDim.new(0, 1) sna_t.Name = "\68\114\111\112\100\111\119\110\72\111\108\100\101\114\85\73\67\111\114\110\101\114" sna_t.Parent = na_t fsna_.Name = "\68\114\111\112\100\111\119\110\73\109\97\103\101" fsna_.Parent = na_t fsna_.BackgroundColor3 = Color3.fromRGB(255, 255, 255) fsna_.BackgroundTransparency = 1.000 fsna_.BorderSizePixel = 0 fsna_.Position = UDim2.new(0, 5, 0, 3) fsna_.Size = UDim2.new(0, 18, 0, 18) fsna_.Image = "\114\98\120\97\115\115\101\116\105\100\58\47\47\55\56\51\49\50\56\50\55\48\57" fsna_.ImageColor3 = Color3.fromRGB(200, 200, 200) omjch.Name = "\68\114\111\112\100\111\119\110\72\111\108\100\101\114\84\105\116\108\101" omjch.Parent = na_t omjch.BackgroundColor3 = Color3.fromRGB(255, 255, 255) omjch.BackgroundTransparency = 1.000 omjch.BorderSizePixel = 0 omjch.Position = UDim2.new(0, 25, 0, 0) omjch.Size = UDim2.new(0, 175, 0, 25) omjch.Font = Enum.Font.GothamSemibold omjch.Text = dropdowntitle or "\68\114\111\112\100\111\119\110\32\124\32\68\114\111\112\32\77\101\32\33" omjch.TextColor3 = Color3.fromRGB(180, 180, 180) omjch.TextSize = 13.000 omjch.TextXAlignment = Enum.TextXAlignment.Left igfsn.Name = "\68\114\111\112\100\111\119\110\66\117\116\116\111\110" igfsn.Parent = na_t igfsn.BackgroundColor3 = Color3.fromRGB(255, 255, 255) igfsn.BackgroundTransparency = 1.000 igfsn.BorderSizePixel = 0 igfsn.Size = UDim2.new(0, 350, 0, 25) igfsn.ZIndex = 2 igfsn.Font = Enum.Font.SourceSans igfsn.Text = "" igfsn.TextColor3 = Color3.fromRGB(0, 0, 0) igfsn.TextSize = 14.000 bigfs.Name = "\68\114\111\112\100\111\119\110\73\110" bigfs.Parent = na_t bigfs.BackgroundColor3 = Color3.fromRGB(255, 255, 255) bigfs.BackgroundTransparency = 1.000 bigfs.BorderSizePixel = 0 bigfs.Position = UDim2.new(0, 0, 0, 25) bigfs.Size = UDim2.new(0, 350, 0, 1) dbig.Name = "\68\114\111\112\100\111\119\110\73\110\76\105\115\116" dbig.Parent = bigfs dbig.SortOrder = Enum.SortOrder.LayoutOrder pdbi.Name = "\68\114\111\112\100\111\119\110\83\101\108\101\99\116\101\100\84\105\116\108\101" pdbi.Parent = na_t pdbi.BackgroundColor3 = Color3.fromRGB(39, 86, 144) pdbi.BorderSizePixel = 0 pdbi.Position = UDim2.new(0, 345, 0, 2) pdbi.Size = UDim2.new(0, -50, 0, 20) pdbi.Font = Enum.Font.GothamSemibold pdbi.Text = "\78\79\78\69" pdbi.TextColor3 = Color3.fromRGB(200, 200, 200) pdbi.TextSize = 12.000 hpdbi.Name = "\68\114\111\112\100\111\119\110\72\111\108\100\101\114\85\73\83\116\114\111\107\101" hpdbi.Parent = eqom hpdbi.ApplyStrokeMode = Enum.ApplyStrokeMode.Border hpdbi.Color = Color3.fromRGB(35, 78, 130) hpdbi.LineJoinMode = Enum.LineJoinMode.Round hpdbi.Thickness = 1.6 hpdbi.Transparency = 0 hpdbi.Enabled = true hpdbi.Archivable = true igfsn.MouseButton1Click:Connect(function() na_t:TweenSize(UDim2.new(0, 350, 0, 25 + dbig.AbsoluteContentSize.Y), "\73\110\79\117\116", "\81\117\97\100", 0.08, true) end) pdbi.Size = UDim2.new(0, 0 - pdbi.TextBounds.X - 5, 0, 20) pdbi:GetPropertyChangedSignal("\84\101\120\116"):Connect(function() pdbi.Size = UDim2.new(0, 0 - pdbi.TextBounds.X - 5, 0, 20) end) for listindex, listvalue in next, list do local mjchp = Instance.new("\84\101\120\116\66\117\116\116\111\110") mjchp.Name = listvalue or "\76\105\115\116\66\117\116\116\111\110" mjchp.Parent = bigfs mjchp.BackgroundColor3 = Color3.fromRGB(39, 86, 144) mjchp.BorderSizePixel = 0 mjchp.Size = UDim2.new(0, 350, 0, 25) mjchp.AutoButtonColor = false mjchp.Font = Enum.Font.GothamSemibold mjchp.Text = listvalue or "\76\105\115\116" mjchp.TextColor3 = Color3.fromRGB(180, 180, 180) mjchp.TextSize = 14.000 mjchp.MouseButton1Click:Connect(function() na_t:TweenSize(UDim2.new(0, 350, 0, 25), "\73\110\79\117\116", "\81\117\97\100", 0.08, true) pdbi.Text = mjchp.Text pcall(function() dropdowncallback(mjchp.Text) end) end) end local jchpd = {} function jchpd:RefreshDropdown(newlist) newlist = newlist or {} for _, alllist in pairs(bigfs:GetChildren()) do if alllist:IsA("\84\101\120\116\66\117\116\116\111\110") then alllist:Destroy() end end for newlistindex, newlistvalue in next, newlist do local mjchp = Instance.new("\84\101\120\116\66\117\116\116\111\110") mjchp.Name = newlistvalue or "\76\105\115\116\66\117\116\116\111\110" mjchp.Parent = bigfs mjchp.BackgroundColor3 = Color3.fromRGB(39, 86, 144) mjchp.BorderSizePixel = 0 mjchp.Size = UDim2.new(0, 350, 0, 25) mjchp.AutoButtonColor = false mjchp.Font = Enum.Font.GothamSemibold mjchp.Text = newlistvalue or "\76\105\115\116" mjchp.TextColor3 = Color3.fromRGB(180, 180, 180) mjchp.TextSize = 14.000 mjchp.MouseButton1Click:Connect(function() na_t:TweenSize(UDim2.new(0, 350, 0, 25), "\73\110\79\117\116", "\81\117\97\100", 0.08, true) pdbi.Text = mjchp.Text pcall(function() dropdowncallback(mjchp.Text) end) end) end end return jchpd end function big:CreateLabel(labeltitle) local omjch = Instance.new("\84\101\120\116\76\97\98\101\108") omjch.Name = labeltitle or "\68\114\111\112\100\111\119\110\72\111\108\100\101\114\84\105\116\108\101" omjch.Parent = sna omjch.BackgroundColor3 = Color3.fromRGB(255, 255, 255) omjch.BackgroundTransparency = 1.000 omjch.BorderSizePixel = 0 omjch.Position = UDim2.new(0, 5, 0, 190) omjch.Size = UDim2.new(0, 350, 0, 15) omjch.Font = Enum.Font.GothamSemibold omjch.Text = labeltitle or "\84\104\105\115\32\73\115\32\65\32\68\101\115\99\114\105\112\116\105\111\110" omjch.TextColor3 = Color3.fromRGB(150, 150, 150) omjch.TextSize = 13.000 omjch.TextXAlignment = Enum.TextXAlignment.Left local qomjc = {} function qomjc:ChangeLabel(newlabeltitle) omjch.Text = newlabeltitle end return qomjc end return big end return tlreq end return lreqo end local eqomj = loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\66\111\99\117\115\76\117\107\101\47\85\73\47\109\97\105\110\47\83\84\88\47\77\111\100\117\108\101\46\76\117\97"))() local reqom = loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\66\111\99\117\115\76\117\107\101\47\85\73\47\109\97\105\110\47\83\84\88\47\67\108\105\101\110\116\46\76\117\97"))() local lreqo = a_:CreateWindow("\68\97\72\111\111\100") local tlreq = lreqo:NewPage("\77\97\105\110") local _t = tlreq:NewSection("\67\82\69\68\73\84\32\85\114\32\82\49\50\50") _t:CreateDropdown("\83\116\97\110\100", {"\71\111\108\100\32\69\120\112\101\114\105\101\110\99\101" [In Another Time] ,"\83\105\108\118\101\114\32\67\104\97\114\105\111\116","\67\114\97\122\121\32\68\105\97\109\111\110\100" ,"\77\97\103\105\99\105\97\110\115\32\82\101\100" ,"\84\104\101\32\72\97\110\100" ,"\83\116\105\99\107\121\32\70\105\110\103\101\114\115" ,"\83\116\97\114\32\80\108\97\116\105\110\117\109\58\32\84\104\101\32\87\111\114\108\100" ,"\87\104\105\116\101\115\110\97\107\101" ,"\75\105\110\103\32\67\114\105\109\115\111\110" ,"\83\116\97\114\32\80\108\97\116\105\110\117\109" ,"\84\104\101\32\87\111\114\108\100"},function(j) _G.Stand = j end)  local a_tlre = _t:CreateLabel('Stand : '..game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Data.AbilityName.Value) spawn(function() while wait() do  pcall(function() a_tlre:ChangeLabel('Stand : '..game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Data.AbilityName.Value) end) end end) _t:CreateToggle("\83\116\97\114\116\32\70\97\114\109",function(m) shared.Stand = m while shared.Stand do wait() pcall(function() function g(i) if i then if game.Players.LocalPlayer.Backpack:FindFirstChild("\83\116\97\110\100\32\65\114\114\111\119") == nil then game:GetService("\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101").ItemGiver.GiveArrow:FireServer() elseif game.Players.LocalPlayer.Character:FindFirstChild("\83\116\97\110\100\32\65\114\114\111\119") == nil then game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Character.Humanoid:EquipTool(game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Backpack:FindFirstChild("\83\116\97\110\100\32\65\114\114\111\119")) end end end if game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Data.AbilityName.Value == _G.Stand then  brickColor = BrickColor.new("\82\101\97\108\108\121\32\114\101\100") game.StarterGui:SetCore("\67\104\97\116\77\97\107\101\83\121\115\116\101\109\77\101\115\115\97\103\101", { Text = "\91\69\114\114\111\114\93\32\83\116\97\110\100\32\97\108\114\101\97\100\121\32\97\99\113\117\105\114\101\100"; Color = brickColor.Color; FontSize = Enum.FontSize.Size96;  }) shared.Stand = false       return end repeat wait() pcall(function() g(true) if game.Players.LocalPlayer.Character:FindFirstChild("\83\116\97\110\100\32\65\114\114\111\119") then if game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.ToolGui.Arrow.Visible == true then for i,v in ipairs(game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.ToolGui.Arrow:GetDescendants()) do if v.Name == "\89\101\115" then v.Parent = game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.ToolGui if game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.ToolGui:FindFirstChild("\89\101\115") then v.Position = UDim2.new(0, 0, 0, 0) v.TextTransparency = 1 end  end end if game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.ToolGui:FindFirstChild("\89\101\115") then game:GetService('VirtualUser'):ClickButton1(Vector2.new(game:GetService("\80\108\97\121\101\114\115").LocalPlayer.PlayerGui.ToolGui.Yes.Position)) end end end end) until not shared.Stand or game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Data.AbilityName.Value == _G.Stand if game:GetService("\80\108\97\121\101\114\115").LocalPlayer.Data.AbilityName.Value == _G.Stand then  brickColor = BrickColor.new("\66\114\105\103\104\116\32\103\114\101\101\110") game.StarterGui:SetCore("\67\104\97\116\77\97\107\101\83\121\115\116\101\109\77\101\115\115\97\103\101", { Text = "\33\33\32\78\111\116\105\102\105\99\97\116\105\111\110\32\33\33"; Color = brickColor.Color; FontSize = Enum.FontSize.Size96;  }) shared.Stand = false end end) end end) return Dino
