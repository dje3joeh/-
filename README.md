name="Humanoid"
robo=script.Parent:cione()
While true do
	Wait(1)
	if script.Parent.Humanoid<1 then
		    robot=robo:clone()
		    robot.Parent=script.Parent
		    robot:makeJoints()
		    script.Parent:remove()
  end
end
# -
