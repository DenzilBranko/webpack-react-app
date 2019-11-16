

//if you get the CleanWebpackPlugin is not a constructor fallow below solution
//change import method in header file from 
const  CleanWebpackPlugin  = require('clean-webpack-plugin');
to 
const { CleanWebpackPlugin } = require('clean-webpack-plugin');