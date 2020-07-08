# https://rclone.org/drive/
# https://rclone.org/drive/#making-your-own-client-id

1.Tạo project trên google account: https://console.developers.google.com/
2.Enable Google Drive API 
3. Google Console -> Credentials -> Create Credentials -> Service Account
4.Add key -> download xuống local . Rồi tải lên server ví dụ /root/.rclone/gdrive.json
5. Cài cắm rclone
6. Config rclone làm theo hướng dẫn. Chú ý service_account_file nhập đường dẫn của key.json file ở bước 4
7. Test: rclone ls remote: 
