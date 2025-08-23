# Troubleshooting

### ❌ Backend doesn’t run
- Ensure you’re using the packaged `WebDS.exe`
- If building yourself, install dependencies with `npm install`

### ❌ Frontend doesn’t load
- Verify files are in the `deploy/` folder of the robot project
- Check that the robot is connected via USB or network

### ❌ No robot communication
- Make sure your laptop is on the same network as the RoboRIO
- Ensure firewall is not blocking UDP 1110/1150 ports
