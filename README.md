Graal Guild System with SQLite

--`Guild` Table--
`
Create table guild (
GuildName varchar(255) not null primary key, 
OwnerGraalId varchar(255) not null unique,
MemberCount int not null default 1
);`

--`Guild_GuildMember` Table--
`
Create table guild_guildmember (
GuildName varchar(255) not null,
MemberGraalId varchar(255) not null
);`

--`GuildMember` Table-- 
`
Create table guildmember (
GraalId varchar(255) not null primary key
);`


Create 'AdminPanel' weapon and add to your weapons.
Press 'o' to open the admin panel.
