docker run --name session7_app -p 8086:80 -e "ConnectionStrings:FoodDB"="Server=dblocal;Port=3306;Database=fooddb; Uid=test; Pwd=123456" --link dblocal -it session7_img



