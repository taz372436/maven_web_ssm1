# maven_web_ssm1
maven的ssm加后台分页
CREATE TABLE `tt_user` (  
  `USER_ID` int(11) NOT NULL AUTO_INCREMENT,  
  `USER_NAME` char(30) NOT NULL,  
  `USER_PASSWORD` char(10) NOT NULL,  
  `USER_EMAIL` char(30) NOT NULL,  
  PRIMARY KEY (`USER_ID`),  
  KEY `IDX_NAME` (`USER_NAME`)  
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8  

INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (1, '尚海涛', 'shtace', 'shtace@sina.com');  

select * from tt_user 

INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (2, 'ass', '123', 'fff@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (3, 'fff', 'cadg', 'fwsfg@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (4, 'ggg', 'cscs', 'fsaf@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (5, 'arthur', 'csas', 'fsaff@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (6, 'kkk', 'yuh78', 'fdfas@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (7, 'lll', 'cvff', 'fsaf@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (8, 'hhh', 'gvv', 'lin@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (9, 'jjjj', 'dfsc', 'ling2008@126.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (10, '222', 'uih6', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (11, 'www', 'tgggg', '43qt@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (12, 'eee', 'ggg', '14e23@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (13, 'rrr', 'gg', '122@qq.com'); 
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (14, 'ttt', 'dsv', '34r@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (15, 'yyy', 'vvfdz', '456@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (16, 'uuu', 'vz', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (17, 'iii', 'zvz', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (18, 'ooo', 'dvs', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (19, 'apple', 'czvcx', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (20, 'apple', 'xvzczv', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (21, 'apple', 'cz', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (22, 'apple', 'cxz', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (23, 'apple', 'czv', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (24, 'apple', 'C', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (25, 'apple', 'dfdsf', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (26, 'apple', 'vvf', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (27, 'apple', '45', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (28, 'apple', '5677', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (29, 'apple', '8', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (30, 'apple', '8', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (31, 'apple', '0h', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (32, 'apple', 'vf', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (33, 'apple', 'sfd', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (34, 'apple', '5yh', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (35, 'apple', 'bdf', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (36, 'apple', 'gers', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (37, 'apple', '89', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (38, 'apple', '5t', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (39, 'apple', 'gse', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (40, 'apple', 'gs', 'ff@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (41, 'apple', 'bs', '4454@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (42, 'apple', 'fs', '3445@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (43, 'apple', 'bs', '354@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (44, 'apple', 'fsd', '567@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (45, 'apple', 'sd', '45567@qq.com');
INSERT INTO tt_user (USER_ID, USER_NAME, USER_PASSWORD, USER_EMAIL) VALUES (46, 'apple', 'gs', '456@qq.com');


