{\rtf1\ansi\ansicpg1252\cocoartf2513
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww17820\viewh12380\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs36 \cf0 Pipeline \{\
	agent any\
	\
	stages \{\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf0 		stage(\'93Checkout git code\'94) \{\
			steps\{\
				git branch: \'91main\'92, url: \'91https://github.com/NinaDimitrova/WorkShop2_Jenkins\'94	\
			\}	\
		\}\
		stage(\'93Setup dot net 6\'94)\{\
			steps\{\
					bat \'91 \'91 \'91\
					echo Installing .NET SDK 6.0\
					choco install dotnet-sdk -y \'97version=6.0.100\
			\'91 \'91 \'91\
		\}\
		\
		\}\
		stage(\'93Install nugget packages\'94)\{\
			steps\{\
				bat \'91dotnet restore SeleniumIde.sln\'92\
			\}\
		\}\
		stage(\'93Build the project)\{\
			steps\{\
				bat \'91dotnet build SeleniumIde.sln\'92\
			\}\
		\}\
		stage(\'93Run tests\'94)\{\
			steps\{\
				bat \'91dotnet test SeleniumIde.sln \'97logger \'93trx; LogFileName=TestResults.trx\'94\'92\
			\}\
		\}\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf0 	\}\
	post\{\
		always\{\
			archiveArtifacts artefacts: \'91**/TesResults/*.trx\'92\
			allowEmptyArchive: true\
			step([\
				$class: \'91MSTestPublisher\'92,\
				testResultsFile: \'91**/TesResults/*.trx\'92		\
			])\
	\}\
\}\
\}\
\
}