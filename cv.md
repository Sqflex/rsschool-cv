# **Golubev Egor**

![My photo](https://sun9-47.userapi.com/c849328/v849328980/199ac5/DxIO2cNYVpo.jpg)

## **Contacts**
* _Telephone and messengers(Telegram,Viber)_: +375447387513
* _Email_: egorkazgorki2@gmail.com
* _VK_: [Егор Голубев](https://vk.com/redeyedgiftia)

## **Summary**

I have spent the last two years developing my skills as developer, but dont even found my own way in the world of programming languages. All my friends know me as patient, kind and responsible person. I have one secret ability - to learn fast and it makes my life more easier in a lot of hobbies.

## **Skills**

* Programming languages
    * Novice in:
        1. JS
        2. Assembly
    * Learned a lot:
        1. Java
        2. Python
        3. C#
    * Databases:
        1. MySQL

## Code Sample 
Code Sample from my old java project:

    public void CreateNewTransport(String TransportType, String TransportName, Integer TransportCost) {
        String insert = "INSERT INTO " + constant.USER_TABLE + "(" + constant.FACTORY_TRANSPORT + "," + constant.TRANSPORT_NAME + "," +
                constant.TRANSPORT_COST + ")" + "VALUES(?,?,?)";


        try {
            PreparedStatement prST = getDatabaseConnectionbConnection().prepareStatement(insert);
            prST.setString(1, TransportType);
            prST.setString(2, TransportName);
            prST.setInt(3, TransportCost);
            prST.executeUpdate();
        } catch (SQLException e) {
            e.printStackTrace();
        } catch (ClassNotFoundException e) {
            e.printStackTrace();
        }


    }

## Experience

* Working with Telegram API:
    * Schedule Bot (on development stage)
* Laboratory practise on python, C#
* Java project using MySQL

## Educational

**Belarussian State University of Informatics and Radioelectronics**                  

(2017-2021)

*FACULTY OF COMPUTER SYSTEMS AND NETWORKS*    

*Computer science and programming technology*

## English level

B1 or Intermediate.

